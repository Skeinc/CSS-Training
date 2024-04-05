# CSS Текст

Текст является ключевым элементом любой веб-страницы, и его оформление играет важную роль в создании привлекательного и удобочитаемого контента. CSS предоставляет множество возможностей для стилизации текста, включая выбор шрифтов, изменение размеров, в цветов и многие другие.

## Основы CSS для оформления текста

Основные свойства CSS, используемые для оформления текста, включают в себя:

- **font-family:** Определяет шрифт текста.

```
span {
    font-family: Arial, sans-serif;
}
```

- **font-size:** Устанавливает размер шрифта.

```
span {
    font-family: Arial, sans-serif;
    font-size: 14px;
}
```

- **font-weight:** Определяет насыщенность шрифта (например, обычный, полужирный).

```
span {
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: bold;
}
```

## Выравнивание текста

- **text-align:** Управляет выравниванием текста.

```
span {
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: bold;
    text-align: center;
}
```

- **text-align-last:** Свойство определяет, как выравнивать последнюю строку текста:

```
p {
    text-align-last: justify;
}
```

- **direction и unicode-bidi:** можно использовать для изменения направления текста элемента:

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
}
```

- **vertical-align:** задает вертикальное выравнивание элемента.

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
    vertical-align: baseline;
}
```

## Межстрочный интервал и межбуквенный интервал

- **line-height:** Устанавливает высоту строки.

```
span {
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: bold;
    text-align: center;
    line-height: 1.5;
}
```

- **letter-spacing:** Устанавливает расстояние между буквами.

```
span {
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: bold;
    text-align: center;
    line-height: 1.5;
    letter-spacing: 2px;
}
```

- **text-indent:** используется для указания отступа первой строки текста:

```
.text {
    text-indent: 50px;
}
```

- **word-spacing:** используется для указания пробела между словами в тексте.

```
.text {
    text-indent: 50px;
    word-spacing: 10px;
}
```

- **white-space:** определяет, как обрабатывается пробел внутри элемента.

```
.text {
    text-indent: 50px;
    word-spacing: 10px;
    white-space: nowrap;
}
```

## Текстовые тени и декорации

- **text-shadow:** Создает тень для текста.

```
span {
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: bold;
    text-align: center;
    line-height: 1.5;
    letter-spacing: 2px;
    text-shadow: 1px 1px 2px #000;
}
```

- **text-decoration:** Управляет декорациями текста (например, подчеркивание, зачеркивание).

```
span:hover {
    text-decoration: underline;
}
```

- **text-decoration-line:** используется для добавления к тексту декоративной линии.

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
    vertical-align: baseline;
    text-decoration-line: overline;
}
```

- **text-decoration-color:** используется для установки цвета линии оформления.

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
    vertical-align: baseline;
    text-decoration-line: overline;
    text-decoration-color: red;
}
```

- **text-decoration-style:** используется для задания стиля линии оформления.

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
    vertical-align: baseline;
    text-decoration-line: overline;
    text-decoration-color: red;
    text-decoration-style: solid;
}
```

- **text-decoration-thickness:** используется для задания толщины линии оформления:

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
    vertical-align: baseline;
    text-decoration-line: overline;
    text-decoration-color: red;
    text-decoration-style: solid;
    text-decoration-thickness: 5px;
}
```

## Преобразование текста

- **text-transform:** используется для указания в тексте прописных и строчных букв.

Его можно использовать для преобразования всего в прописные или строчные буквы или для перевода первой буквы каждого слова в заглавную:

```
p {
    text-align-last: justify;
    direction: rtl;
    unicode-bidi: bidi-override;
    vertical-align: baseline;
    text-decoration-line: overline;
    text-decoration-color: red;
    text-decoration-style: solid;
    text-decoration-thickness: 5px;
    text-transform: uppercase;
}
```

## Заключение

CSS предоставляет широкий спект возможностей для оформления текста на веб-страницах. В этой статье мы рассмотрели основные свойства и методы CSS для стилизации текста, включая выбор шрифтов, размеров, цветов, выравнивание, межстрочный интервал и многие другие.