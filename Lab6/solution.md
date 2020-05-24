Зайдем в любую категорию и определим количество столбцов способом, описанным в Lab3.<br/>
В данном случае у нас 2 столбца<br/><br/>
<img src="screenshot1.png"> <br/><br/>
Проверим, какие из столбцов содержат текст.<br/><br/>
<img src="screenshot2.png"> <br/><br/>
Подходит только 2 столбец.<br/><br/>
<img src="screenshot3.png"> <br/><br/>
Введем запрос 'UNION SELECT NULL,username ||'~'|| password FROM users--<br/>
Получим данные вида логин~пароль.<br/><br/>
<img src="screenshot4.png"><br/><br/>
Возьмем данные администратора и залогинимся с помощью них.<br/><br/>
<img src="screenshot5.png"><br/><br/>
Мы смогли зайти от имени администратора.<br/><br/>
<img src="screenshot6.png"><br/><br/>
