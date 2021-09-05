# Лабораторная 6. Организовать архитектуру

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdwCqWyykBtninwkeGUbkmCrOSl-Z_snJNhyn2mMqeZLxit0aR38XopULKshOAJws-KE8&usqp=CAU" width="300">

<br>
<br>

## Базовые требования:

- Необходимо вынести повторяющиеся части интерфейса в отдельные виджеты и переиспользовать
- Каждый виджет/экран должен находится в отдельном файле с одноименным названием
- Для каждой сущности в данных должен быть создан свой класс, в том числе определяющий копирование, считывание из/в Map/Json
- Необходимо выделить отдельный класс для работы с api
- Необходимо [выбрать систему для управления данными](https://flutter.dev/docs/development/data-and-backend/state-mgmt/options) в приложении (State Management) и переписать код в соответствии с ее парадигмами. Рекомендуется взять [BLoC](https://flutter.dev/docs/development/data-and-backend/state-mgmt/options#bloc--rx).
- Лабораторная работа должна быть залита на github

<br>

## Полезные материалы:

- https://fluttersamples.com/
- https://flutter.dev/docs/development/data-and-backend/json#serializing-json-inside-model-classes
- https://marketplace.visualstudio.com/items?itemName=BendixMa.dart-data-class-generator
