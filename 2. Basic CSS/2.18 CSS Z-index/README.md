# CSS z-index

CSS свойство ``z-index`` - это мощный инструмент, который позволяет управлять порядком наложения элементом на веб-странице. Оно определяет как элементы находятся в пространстве, позволяя вам создавать сложные макеты и управлять их визуальным представлением.

## Определение свойства z-index

Свойство ``z-index`` - это CSS свойство, которое определяет порядок наложения элементом по оси Z, т.е глубину слоя. Элементы с более высоким ``z-index`` будут находиться выше по стеку, чем элементы с меньшим ``z-index``.

```
img {
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
}
```

**Примечание:** Свойство ``z-index`` работает только с позиционированными элементами (позиция: абсолютная, относительная, фиксированная или липкая) и гибкими элементами (элементами, которые являются прямыми дочерними элементами).

## Управление порядком наложения

Вы можете использовать ``z-index`` для управления порядком наложения элементов на странице. Это особенно полезно при работе с перекрывающимися элементами.

```
.header {
    position: relative;
    z-index: 2;
}

.sidebar {
    position: relative;
    z-index: 1;
}

.content {
    position: relative;
    z-index: 3;
}
```

## Применение z-index с позиционированием

Обычно ``z-index`` применяется вместе с позиционированием элементов, таким как ``relative``, ``absolute`` или ``fixed``, чтобы иметь контроль над их местоположением.

## Значения z-index

- Положительные значения: Элементы с большим ``z-index`` находятся выше по стеку, чем элементы с меньшим ``z-index``;
- Отрицательные значения: Элементы с отрицательным ``z-index`` могут быть перекрыты элементами с положительным ``z-index``;
- Значение по умолчанию: ``auto``, элементы находятся в порядке, определенном порядком в HTML-коде.

## Заключение

CSS свойство ``z-index`` - это мощный инструмент для управления порядком наложения элементов на веб-странице. В этой статье мы рассмотрели основные его аспекты, включая определение, управление порядком наложения, применение с позиционированием и значения.