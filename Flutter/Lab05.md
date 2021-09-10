# Лабораторная 5. Организовать архитектуру

Лабораторная работа является продолжением лабораторных работ: [1,](./Lab01.md) [2,](./Lab02.md) [3,](./Lab03.md) [4](./Lab04.md)
<br>
<br>
Необходимо привести имеющийся код "в порядок" и организовать архитектуру

<p align="center">
  <img src="https://miro.medium.com/max/831/1*Ih7zWqPcTwGkZXGoxJOH2A.png" width="550">
</p>

## Критерии приемки:

- Необходимо вынести повторяющиеся части интерфейса в отдельные виджеты и переиспользовать
- Каждый виджет/экран должен находится в отдельном файле с одноименным названием
- Для каждой сущности данных должен быть создан свой класс
- Необходимо выделить отдельный класс для работы с _api_
- Необходимо [выбрать систему для управления данными](https://flutter.dev/docs/development/data-and-backend/state-mgmt/options) в приложении (State Management) и переписать код в соответствии с ее парадигмами. Рекомендуется взять [BLoC](https://flutter.dev/docs/development/data-and-backend/state-mgmt/options#bloc--rx).
- Лабораторная работа должна быть залита на **github**

<br>

## Полезные материалы:

- Используйте встроенную [кодогенерацию](https://flutter.dev/docs/development/data-and-backend/json#serializing-json-inside-model-classes) или [плагин](https://marketplace.visualstudio.com/items?itemName=BendixMa.dart-data-class-generator) для сериализации данных во flutter
- Можно использовать плагин [flutter_bloc](https://pub.dev/packages/flutter_bloc) для более удобной работой с BLoC
- Ознакомиться с вариантами арихитектур flutter можно на сайте [fluttersamples](https://fluttersamples.com/)
