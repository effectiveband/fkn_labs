# Лабораторная 1. Сверстать экран со списком героев

Необходимо сверстать экран на статичных данных со списком геров из вселенной Marvel 

## При реализации экрана рекомендуется использовать: 
- [RecyclerView](https://developer.android.com/reference/kotlin/androidx/recyclerview/widget/RecyclerView) или библиотеку [DiscreteScrollView](https://github.com/yarolegovich/DiscreteScrollView) для реализации прокручиваемого списка
- [ConstraintLayout](https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout) для гибкого позиционирования компонентов
- [TextView](https://developer.android.com/reference/android/widget/TextView) компонент для отображения текста 
- [ImaveView](https://developer.android.com/reference/android/widget/ImageView) компонент для отображения изображений

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
- Лабораторная работа должна быть залита на **github**

<br>

## Полезные материалы:

- Рекомендуется пройти codelab [Use RecyclerView to display a scrollable list](https://developer.android.com/codelabs/basic-android-kotlin-training-affirmations-app#0) и [Display a list of images using cards](https://developer.android.com/codelabs/basic-android-kotlin-training-affirmations-app-polish#0) для лучшего освоения материала
