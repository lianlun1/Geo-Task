Приложение состоит из 3х экранов
1. Сплеш (картинка с неоднородным фоном, клонировная на весь экран)


2. Activity ввода начальной и конечной точки
Содержит:
а) 2 таба Откуда и Куда.
Внутри табов:
*Поле ввода для поиска при вводе геоенкодер определяет вариант и координаты (до 7 штук)
*Список найденных вариантов (видимы 3 шт остальное скролл). Клик по элементу выбирает его.
*Карта показывает место выбранного варианта на карте
б) Кнопка поиска пути. При нажатии переход на Форму результата.


3. Форма результата:
Карта, смасштабированная таким образом что включает:
*Местоположение пользователя по геолокации
*Путь от точки Откуда в точку Куда, полученный с помошью прямого запроса (HTTP GET) к Google сервису DirectionsAPI (https://developers.google.com/maps/docu ... irections/).

Для демонстрации добавьте API-ключ:

1. Получите API-ключ 
2. Откройте local.properties
3. Добавьте одну строку в local.properties которая выглядит как API_KEY = YOUR_API_KEY
