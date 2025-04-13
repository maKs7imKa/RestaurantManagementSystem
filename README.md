Project/
├── app.js                     # Головний файл додатку
├── .gitignore                 # Файл для ігнорування певних файлів/папок у Git
├── package.json               # Конфігурація проекту Node.js
├── README.md                  # Документація проекту
├── config/
│   └── database.js            # Конфігурація бази даних
├── controllers/
│   ├── adminController.js     # Контролер для адміністративних функцій
│   ├── bookingController.js   # Контролер для бронювання
│   ├── indexController.js     # Контролер для головної сторінки
│   └── orderController.js     # Контролер для замовлень
├── middleware/
│   ├── isAuthenticated.js     # Middleware для перевірки автентифікації
│   └── isAdmin.js             # Middleware для перевірки прав адміністратора
├── models/
│   ├── CartItem.js            # Модель для елементів кошика
│   ├── Dish.js                # Модель для страв
│   ├── Inventory.js           # Модель для складу
│   ├── Invoice.js             # Модель для накладних
│   ├── Order.js               # Модель для замовлень
│   ├── Reservation.js         # Модель для бронювань
│   ├── Session.js             # Модель для сесій
│   └── User.js                # Модель для користувачів
├── public/
│   ├── admin_dishes_add.css   # Стили для додавання страв
│   ├── admin_inventory.css    # Стили для управління складом
│   ├── admin_orders.css       # Стили для сторінки замовлень
│   ├── admin_panel.css        # Стили для адміністративної панелі
│   ├── booking_table.css      # Стили для сторінки бронювання
│   ├── home_page.css          # Стили для головної сторінки
│   └── profile.css            # Стили для сторінки профілю
├── routes/
│   ├── admin.js               # Маршрути для адміністративних функцій
│   ├── booking.js             # Маршрути для бронювання
│   ├── index.js               # Головні маршрути
│   ├── order.js               # Маршрути для замовлень
│   └── auth.js                # Маршрути для автентифікації
├── scripts/
│   └── addAdmin.js            # Скрипт для додавання адміністратора
├── views/
│   ├── admin.ejs              # Шаблон для адміністративної панелі
│   ├── booking.ejs            # Шаблон для сторінки бронювання
│   ├── cart.ejs               # Шаблон для кошика
│   ├── dishes.ejs             # Шаблон для управління стравами
│   ├── home.ejs               # Шаблон для головної сторінки
│   ├── inventory.ejs          # Шаблон для управління складом
│   ├── order.ejs              # Шаблон для сторінки замовлення
│   ├── orders.ejs             # Шаблон для перегляду замовлень
│   └── profile.ejs            # Шаблон для сторінки профілю
└── syncDatabase.js            # Скрипт для синхронізації бази даних