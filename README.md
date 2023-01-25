#Проект "Мой Силант"

Регистрация доступна только через панель администратора, пользователь не может самостоятельно зарегистрироваться. 

В файле "1.txt" предоставлены примеры, где:
guest - клиент,
service - сервисная организация,
manager - менеджер.

Данные в базу данных заведены согласно таблицы из ТЗ.

	#Основные страницы
http://127.0.0.1:8000/ - домашняя страница

http://127.0.0.1:8000/user/ - общая информация о технике

http://127.0.0.1:8000/to/ - информация о ТО

http://127.0.0.1:8000/complaint/ - информация о рекламациях

Кнопка "детали" ведет к подробному описанию. Также доступна фильтрация. Сортировка выполнена в соответствии с ТЗ.

#Доступны данные по API

http://127.0.0.1:8000/api/machine/ - таблица "машина"
http://127.0.0.1:8000/api/to/ - таблица "ТО"
http://127.0.0.1:8000/api/complaint/ - таблица "рекламации"
