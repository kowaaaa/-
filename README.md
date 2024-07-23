# Домашнее задание к занятию «Белый хакинг: тестирование на проникновение»

### Решение 1 (Атака SQL injection) 
### Клиент
Клиент передает информацию о хосте, логин и пароль, информацию о браузер (какой браузер и какая версия), тип и длину содержимого.

[Фото](/2.jpg)

### Сервер
Ответ сервера: предоставляет информацию о сервере, дате, показывает код.

[Фото](/1.jpg)

### Вывод

Вывод: программа реагирует на нажатия и на изменения страницы. Пакеты отправляются в программу. Сервер читает эти пакеты и показывает информацию в программе. 

### Отчет
[Фото](/3.png)

### Решение 2 (Атака Cross-Site Scripting (XSS))

### Клиент

Клиент передает: информацию о хосте, длину содержимого и его тип содержимого. Информацию о браузере пользователи вид OC. Информацию о уязвимости и её тип.

[Фото](/4.jpg)

### Сервер

Ответ сервера: показывает дату, информацию о сервере, предоставил информацию о платформе приложения, на котором работает сервер, показал локацию и тип содержимого.

[Фото](/5.jpg)

 



















