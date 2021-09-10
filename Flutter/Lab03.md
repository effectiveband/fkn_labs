# Лабораторная 3. Добавить загрузку данных о герое

Лабораторная работа является продолжением [Лабораторной работы 1](./Lab01.md) и [Лабораторной работы 2](./Lab02.md)
<br>
<br>
Необходимо заменить статичные данные на реализованных экранах из _Лабораторной работы 1 и 2_ на данные из сети
<br>
Для получения информации о героях из вселенной **Marvel** необходимо использовать [**Marvel Api**](https://developer.marvel.com/docs#!/public/getCreatorCollection_get_0)

<p align="center">
   <img src="../Images/marvel_ave.jpeg" width="300"></img>
</p>

## При выполнении лабораторной работы рекомендуется использовать:

- библиотека [dio](https://pub.dev/packages/dio) для работы с сетью с большей функциональностью, чем стандартная библиотека [http](https://pub.dev/packages/http)

## Критерии приемки:

- Для получения списка герое используется **GET** запрос _/public/characters_ из [**Marvel Api**](https://developer.marvel.com/docs#!/public/getCreatorCollection_get_0)
- Для получения информации о герое испольузется **GET** запрос _characters/{characterId}_ из [**Marvel Api**](https://developer.marvel.com/docs#!/public/getCreatorCollection_get_0)
- Если не удается загрузить данные, то необходимо показать ошибку
- Лабораторная работа должна быть залита на **github**

<br>

## Полезные материалы:

- Рекомендуется изучить [добавление работы с сетью](https://flutter.dev/docs/cookbook/networking/fetch-data) из документации
- Дополнительно можно просмотреть [видео](https://www.youtube.com/watch?v=pYDjpEHpM8o) с разбором возможностей dio
- При необходимости - ознакомьтесь с [основами](https://www.tutorialspoint.com/http/http_quick_guide.htm) протокола http
