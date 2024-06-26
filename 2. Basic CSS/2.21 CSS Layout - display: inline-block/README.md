# CSS Layout - display: inline-block

CSS свойство ``display: inline-block`` является мощным инструментом для создания гибких и адаптивных макетов веб-страниц. Оно сочетает в себе характеристики как строчных (``inline``), так и блочных (``block``) элементов, предоставляя уникальные возможности для управления расположением и размером элементов.

По сравнению с ``display: inline``, основное отличие состоит в том, что он ``display: inline-block`` позволяет устанавливать ширину и высоту элемента. Кроме того, при использовании ``display: inline-block`` учитываются верхние и нижние поля/отступы, а при ``display: inline`` использовании - нет. По сравнению с ``display: block``, основное отличие состоит в том, что ``display: inline-block`` после элемента не добавляется перенос строки, поэтому элемент может распологаться рядом с другими элементами.

## Определение display: inline-block

Свойство ``display: inline-block`` позволяет элементу вести себя как строчный элемент, при это сохраняя возможность задавать ему размеры (ширину и высоту), что обычно свойственно только блочным элементам.

Пример использования:

```
.block {
    display: inline-block;
    width: 200px;
    height: auto;
    padding: 10px;
    border: 1px dashed grey;
}
```

## Преимущества display: inline-block

- **Гибкость:** Элементы с ``display: inline-block`` располагаются в одну строку, но при этом можно задавать размеры, как для блочных элементов.

- **Отступы:** Поддержка внешних и внутренных отступов, как для блочных элементов.

- **Выравнивание:** Возможность вертикального выравнивания внутри строки.

## Заключение

CSS свойство ``display: inline-block`` предоставляет мощные возможности для создания гибких и адаптивных макетов веб-страниц. Оно сочетает в себе лучшие характеристики как строчных, так и блочных элементов, позволяя создавать горизонтальные меню, галереи изображений и многое другое.