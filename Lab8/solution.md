Заходим на сайт, выбираем любой товар и нажимаем "View details".<br/>
Нажимаем "Check stock" и перехватываем запрос с помощью Burp Suite.<br/><br/>
<img src="screenshot1.png"> <br/><br/>
Отправляем запрос в Repeater.<br/><br/>
<img src="screenshot2.png"> <br/><br/>
Изменяем запрос, отправляем его и получаем ответ.<br/><br/>
<img src="screenshot3.png"><br/><br/>
По добавленному нами адресу находится директория latest. Добавим её в запрос.<br/><br/>
<img src="screenshot4.png"><br/><br/>
Сделав несколько аналогичных итераций, получим полный путь.<br/><br/>
<img src="screenshot5.png"><br/><br/>
<img src="screenshot6.png"><br/><br/>
