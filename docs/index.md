## Grespost

Эта библиотека была вдохновлена идеей написания полноценного конструктора запросов для Postgres. Такого, который позволил бы избавится от использования строковых литералов при описаниии SQL запросов полностью.
Эта библиотека писалась согласно официальной документации Postgres, и включает в себя весь базовый набор функционала для работы с этой СУБД. 
А именно:
- Функции манипуляции и получения данных (`SELECT`, `INSERT`, `DELETE`, `UPDATE`, `VALUES`)
- Функции менеджмента таблиц и индексов (`CREATE`, `DROP`, `ALTER`)
- Методы работы с SQL выражениями. (Унарные и бинарные операторы)
- Огромный набор маппингов стандартных функций
- Методы описания схеммы таблиц и других источников данных
- Тегированные шаблонные строки (На случай если мы что то упустили)

Библиотека разрабатывалась с мыслями о строгой типизации и выведении типов, использовалось всё доступное могущество typescript.

Сама по себе библиотека не умеет делать запросы, однако удовлетворяет интерфейс популярного pg драйвера `node-pg`

### 🔥 Install

```sh
npm i grespost
```

### ⭐️ Show your support

Give a ⭐️ if this project helped you!

### 🤝 Contributing

Contributions, issues and feature requests are welcome!
Feel free to check [issues page](https://github.com/shopmonkeyus/grespost/issues)

#### TODO
- TRANSACTIONS
- PGSQL 14


### 👤 Authors

**shopmonkeyus**

* Website: https://www.shopmonkey.io/
* Github: [@shopmonkeyus](https://github.com/shopmonkeyus)
* LinkedIn: [@https:\/\/www.linkedin.com\/company\/shopmonkey\/](https://linkedin.com/in/https:\/\/www.linkedin.com\/company\/shopmonkey\/)

**Igor Solomakha**

* Github: [@sujimoshi](https://github.com/Sujimoshi)
* LinkedIn: [@Igor Solomakha](https://www.linkedin.com/in/isolomakha/)
