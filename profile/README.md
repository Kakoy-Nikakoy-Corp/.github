# Kakoy-Nikakoy Corporation 🎓

Мы - команда, занимающаяся разработкой решений в области искусственного интеллекта в рамках проектного практикума ИРИТ-РтФ УрФУ. 

Данная организация содержит репозитории нашего последнего на сегодняшний день проекта - **WildlifeCV**.

## WildlifeCV: детекция снежного барса 🏔
В течение весеннего семестра мы разрабатывали веб-сервис для **поиска снежного барса** на материалах с фотоловушек и лесных видеокамер. Наш продукт призван помочь исследователям биоразнообразия в российских нацпарках с изучением и сохранением этого редчайшего вида. 
Благодаря созданному решению учёные смогут не тратить время на отсмотр тысяч кадров и десятков часов видеозаписей, делегировав всю рутинную работу модели компьютерного зрения.

## Структура репозиториев 📜

### Кодовая база веб-сервиса
| Репозиторий | Описание |
| --- | --- |
| [WildlifeCV-backend](https://github.com/Kakoy-Nikakoy-Corp/WildlifeCV-backend) | Бэкенд на FastAPI + инференс и алгоритм RADIC | 
| [WildlifeCV-frontend](https://github.com/Kakoy-Nikakoy-Corp/WildlifeCV-frontend) | Фронтенд на Svelte |
| [WildlifeCV-model](https://github.com/Kakoy-Nikakoy-Corp/WildlifeCV-model) | Скрипты для обучения YOLO26 |


### Вспомогательные утилиты
| Репозиторий | Описание |
| --- | --- |
| [dataset-links-preparer](https://github.com/Kakoy-Nikakoy-Corp/dataset-links-preparer) | Инструмент для подготовки ссылок на датасет для аннотации в Label Studio
| [dedup](https://github.com/Kakoy-Nikakoy-Corp/dedup) | Инструмент для группировки дубликатов изображений
| [image-deteriorator](https://github.com/Kakoy-Nikakoy-Corp/image-deteriorator) | Инструмент для детериорации изображений
| [naturalist-parser](https://github.com/Kakoy-Nikakoy-Corp/naturalist-parser) | Парсер изображений с сайта iNaturalist
| [ru-nature-reserves-parser](https://github.com/Kakoy-Nikakoy-Corp/ru-nature-reserves-parser) | Парсер фото и видео с сайтов российских заповедников
| [stratified-dataset-splitter](https://github.com/Kakoy-Nikakoy-Corp/stratified-dataset-splitter) | Инструмент для разделения и стратификации датасета
| [wi-parser](https://github.com/Kakoy-Nikakoy-Corp/wi-parser) | Парсер изображений с сайта Wildlife Insights


### Артефакты
> По требованию заказчика датасет и веса обученной модели для скачивания не публикуются. Ознакомиться с содержимым датасета можно по [ссылке](https://dataset.irbis.wild1.net).

Все публичные артефакты сохранены в отдельном репозитории [artifacts](https://github.com/Kakoy-Nikakoy-Corp/artifacts).

## Состав команды 😏

Над проектом работали эти замечательные люди:
- **Ахметов Тимур** - Team Lead.
- **Кабанова Валерия** - Data Miner, бизнес-аналитик.
- **Кудашева Диана** - дизайнер, системный аналитик.
- **Мешков Святослав** - Frontend-разработчик.
- **Рафиков Глеб** - Data Miner.
- **Холкин Николай** - Backend-разработчик.
- **Щибрик Максим** - ML-инженер.

## Цветочек 🌷

![Бабыс](https://dataset.irbis.wild1.net/babys.jpg)
