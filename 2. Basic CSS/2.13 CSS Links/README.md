# CSS списки

Списки - это части используемый элемент в веб-дизайне для представления информации в упорядоченной или неупорядоченной форме. CSS предоставляет широкие возможности для стилизации списков, включая изменение маркеров, отступов, цветов и многие другие.

## Списки HTML и свойства списков CSS

В HTML существует два основных типа списков:

- неупорядоченные списки (ul) - элементы списка отмечены маркерами;
- упорядоченные списки (ol) - элементы списка отмечены цифрами или буквами;

Свойства списка CSS позволяют:

- Установите разные маркеры элементов списка для упорядоченных списков;
- Установите разные маркеры элементов списка для неупорядоченных списков;
- Установить изображение в качестве маркера элемента списка;
- Добавление цветов фона в списки и элементы списков.

## Различные маркеры элементов списка

Свойство ``list-style-type`` определяет тип маркера элемента списка.

В следующих примерах показаны некоторые доступные маркеры элементов списка:

```
.list-circle {
    list-style-type: circle;
}

.list-square {
    list-style-type: square;
}

.list-upper-roman {
    list-style-type: upper-roman;
}

.list-lower-alpha {
    list-style-type: lower-alpha;
}
```

## Изображение как маркер элемента списка

Свойство ``list-style-image`` определяет изображение в качестве маркера элемента списка:

```
.list-image {
    list-style-image: url('list-type.png');
}
```

## Размещение маркеров списка

Свойство ``list-style-position`` определяет положение маркеров элементов списка (точек маркированного списка):

```
.list-outside {
    list-style-position: outside;
}

.list-inside {
    list-style-position: inside;
}
```

## Удалить настройки по умолчанию

Свойство ``list-style-type: none`` также можно использовать для удаления маркеров. Обратите внимание, что список также имеет поля и отступы по умолчанию. Чтобы удалить это добавьте ``margin: 0`` и ``padding: 0``:

```
.list-none {
    list-style-type: none;
    margin: 0;
    padding: 0;
}
```

## Список - сокращенное свойство

Свойство ``list-style`` является сокращенным свойством. Он используется для установки всех свойств списка в одном объявлении:

```
ul {
  list-style: square inside url("sqpurple.gif");
}
```

При использовании сокращенного свойства порядок значений свойства следующий:

- ``list-style-type``;
- ``list-style-position``;
- ``list-style-image``;

## Заключение

CSS предоставляет множество возможностей для стилизации списков на веб-страницах. В этой статье мы рассмотрели различные методы улучшения оформления как неупорядоченных, так и упорядоченных списков, включая изменение маркеров, отступов, цветов и использование псевдоэлементов. Практикуйте эти приемы в ваших проектах, чтобы создавать стильные и удобочитаемые списки на ваших веб-страницах.