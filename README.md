# Widget

Команда для старта проекта: yarn start
Номер порта: localhost:7700

Виджет для сайта. Каталог автомобилей. 

Использованы html, scss, js, axios. 

В качестве базы данных был использован фейковый [REST-сервер](https://my-json-server.typicode.com/). [Репозитоий](https://github.com/Oleg-Egorov/database) для хранения базы данных. С помощью библиотеки Axios и метода get подгружаем массив данных, после его получения, создаем список объявлений. Запускаем таймер с авто-прокруткой списка. С помощью кнопок со стрелками мы можем перелистывать объявления с автомобилями самостоятельно.

Для более грамотного написания кода подключаем .stylelintrc и .eslintrc. Сборка проекта сделана через webpack. 