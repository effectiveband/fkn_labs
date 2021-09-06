# Лабораторная 5. Организовать архитектуру

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdwCqWyykBtninwkeGUbkmCrOSl-Z_snJNhyn2mMqeZLxit0aR38XopULKshOAJws-KE8&usqp=CAU" width="300">

<br>
<br>

## Базовые требования:

- Необходимо вынести повторяющиеся части интерфейса в отдельные виджеты и переиспользовать
- Каждый виджет/экран должен находится в отдельном файле с одноименным названием
- Для каждой сущности в данных должен быть создан свой класс или структуру(https://developer.apple.com/documentation/swift/choosing_between_structures_and_classes), в том числе определяющий декодирование(https://developer.apple.com/documentation/swift/decodable), из JSON в entity model
- Необходимо выделить отдельный класс для работы с api
- [Необходимо организовать архитектуру MV*](https://habr.com/ru/company/croc/blog/549590/), рекомендуется использовать MVVM.
- Лабораторная работа должна быть залита на github

<br>

## Полезные материалы:

- https://habr.com/ru/company/badoo/blog/281162/
- https://medium.com/@dev.omartarek/mvp-vs-mvvm-in-ios-using-swift-337884d4fc6fjson#serializing-json-inside-model-classes
- https://www.raywenderlich.com/6587213-alamofire-5-tutorial-for-ios-getting-started