# Ресторанний веб-додаток

## Опис проекту
Цей проект є веб-додатком для ресторану, який дозволяє користувачам переглядати меню, бронювати столики, оформлювати замовлення, а адміністраторам — керувати замовленнями, бронюваннями, запасами та стравами.

---

## Функціонал

### Для користувачів:
1. **Перегляд меню з категоріями:**
   - Користувачі можуть переглядати меню, згруповане за категоріями (наприклад, закуски, основні страви, десерти).
   - Кнопки для фільтрації страв за категоріями.

2. **Додавання страв до кошика:**
   - Користувачі можуть додавати страви до кошика, вказуючи кількість.
   - Відображення загальної суми замовлення в кошику.

3. **Оформлення замовлень:**
   - Користувачі можуть переглядати вміст кошика перед оформленням замовлення.
   - Вибір способу оплати (готівка або картка).
   - Підтвердження замовлення з деталями доставки.

4. **Бронювання столиків:**
   - Вибір дати, часу та кількості гостей.
   - Відображення доступних столиків у ресторані.
   - Можливість додати попереднє замовлення страв.

5. **Перегляд історії замовлень та бронювань у профілі:**
   - Користувачі можуть переглядати свої попередні замовлення та бронювання.
   - Відображення статусу доставки замовлень (Очікується, В процесі, Доставлено).

---

### Для адміністраторів:
1. **Управління замовленнями:**
   - Перегляд списку замовлень із деталями (страва, кількість, адреса доставки, телефон клієнта).
   - Зміна статусу замовлення (Очікується, В процесі, Доставлено, Скасовано).

2. **Управління бронюваннями:**
   - Перегляд списку бронювань із деталями (ім'я клієнта, дата, час, кількість гостей, статус).
   - Можливість скасування бронювання.

3. **Управління запасами:**
   - Відображення списку продуктів із мінімальним, максимальним та поточним запасом.
   - Можливість додавати запаси або заповнювати їх до максимуму.

4. **Управління стравами:**
   - Додавання нових страв до меню із зазначенням назви, опису, ціни та категорії.
   - Редагування існуючих страв.
   - Видалення страв із меню.

---

## Технології
- **Back-end:** Node.js, Express.js
- **Front-end:** EJS, CSS, JavaScript
- **База даних:** MySQL (через Sequelize)
- **Аутентифікація:** Passport.js

---

## Інструкція з розгортання

1. **Клонування репозиторію:**
   ```bash
   git clone <URL репозиторію>
   cd Project

2. **Встановлення залежностей:**
    npm install
    npm start
    http://localhost:3000