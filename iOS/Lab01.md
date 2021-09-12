# Лабораторная 1. Сверстать экран со списком героев

Необходимо сверстать экран на статичных данных со списком геров из вселенной Marvel 

## При выполнении лабораторной работы рекомендуется использовать:
- UIKit
- Для реализации списка [UICollectionView](https://developer.apple.com/documentation/uikit/uicollectionview)
- Для layout ячеек использовать [UICollectionViewFlowLayout](https://developer.apple.com/documentation/uikit/uicollectionviewflowlayouts) из [бибилотеки](https://github.com/akxo/paging-collection-view-layout)
- [UIImageView](https://developer.apple.com/documentation/uikit/uiimageview) компонент для отображения изображения 
- [UILabel](https://developer.apple.com/documentation/uikit/uilabel) компонент для отображения текста

## Примерный вид приложения:

<p align="center">
  <img src="../Images/marvel_main.gif" width=300></img>
</p>

## Критерии приемки:

- Приложение состоит из одного экрана
- В верхней части экрана располагается [логотип **Marvel**](../Images/marvel.png)
- Под логотипом текст **"Choose your hero"**
- На экране имеется прокручиваемый список из ячеек с информацией о герое из вселенной **Marvel**
- Ячейка с информацией о герое имеет фон в виде изображения, каждая ячейка имеет уникальный фон
- Ячейка содержит текст с именем героя из вселенной **Marvel**
- Верстка может быть на storyboard или в коде
- Лабораторная работа должна быть залита на **github**

<br>

## Полезные материалы:
- Рекомендуется изучить примеры использования PagingCollectionViewLayout, устанавливать зависимость через ***cocoapods*** необязательно достаточно добавить файл <code>PagingCollectionViewLayout.swift</code> в Ваш проект
-https://github.com/akxo/paging-collection-view-layout 
- Рекомендуется прочитать autolayout guide  
https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html
- Для верстки в коде рекомендуется использовать [snapkit](http://snapkit.io/) 
примеры и документацию можно найти [здесь](http://snapkit.io/docs/)
