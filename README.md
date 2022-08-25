# My-project

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Описание

:white_check_mark: Для реализации данного проекта использовался фреймворк Vue3    
:white_check_mark: В качестве источника данных использовался API с сайта https://reqres.in/    
:white_check_mark: При запуске проекта добавлен popup с формой авторизации (логин и пароль: admin)    
:white_check_mark: В общем списке пользователей добавлен для каждого пользователя номер телефона (сгенерировано самостоятельно)    
:white_check_mark: Постраничная навигация по 6 шт/стр    
:white_check_mark: Данный список выглядит как аккордеон - есть только ФИО, детали открываются по клику на элемент    
:white_check_mark: Кнопка "Новый пользователь" показывает popup с формой, полями "Имя", "Фамилия", "Номер телефона", "email", "Пароль". В случае незаполненного поля с именем, email или паролем - сообщение об ошибке. В случае успешного добавления пользователя, popup закрыватся, новая запись добавляется в общем списке первой.    
:white_check_mark: Добавлена строка "живого поиска" на странице. Ищем по ФИО. Оставляем на странице только тех, у кого есть вхождение      