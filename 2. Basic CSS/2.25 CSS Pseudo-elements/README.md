# CSS псевдоэлементы

CSS псевдоэлементы являются невероятно мощным и полезным инструментом для стилизации веб-страниц. Они позволяют вам создавать визуальные элементы без необходимости добавлять дополнительные элементы в HTML структуру.

Сначала разберемся, что же такое псевдоэлементы. Они представляют возможность добавления стиля к определенным частям документа, как если бы это были реальные HTML-элементы, но на самом деле их нет в HTML структуре. Они созданы и контролируются полностью с помощью CSS.

Примером псевдоэлемента может быть ``::before`` и ``::after``, которые позволяют вам вставлять контент перед или после элемента, не меняя HTML структуру. Это очень полезно при создании различных визуальных эффектов, таких как иконки, дополнительные элементы формы или обертки для текстового содержимого.

Кроме того, есть псевдоэлементы для работы с текстом, такие как ``::first-letter`` и ``::first-line``, которые позволяют вам применять стили к первому символу или первой строке текстовго элемента. Это может быть полезно для создания интересных визуальных решений для заголовков, цитат или других текстовых блоков.

Есть также псевдоэлементы для работы с анимациями и переходами, например, ``::placeholder``, который позволяет вам стилизовать подписи в полях формы, пока они еще не заполнены. Это отличный способ сделать вашу форму более интуитивно понятной и приятной для пользователя.

Пример:

```
input {
    &::placeholder {
        color: grey;
    }
}

p {
    &::first-line {
        color: rgb(32, 32, 32);
    }

    &::first-letter {
        text-transform: uppercase;
    }
}
```

## Список псевдоэлементов в CSS

- ``::after`` - Вставляет что-либо перед элементом;

- ``::before`` - Вставляет что-либо после элемента;

- ``::first-letter`` - Выбирает первый символ в абзаце;

- ``::first-line`` - Выбирает первую строку в абзаце;

- ``::marker`` - Выбирает маркеры элементов списка;

- ``::selection`` - Выбирает часть элемента, выбранную пользователем;

## Заключение

CSS псевдоэлементы предлагают множество способов улучшения визуального дизайна и взаимодействия с пользователем на вашем сайте, не требуя никаких изменений в HTML-структуре. Они позволяют вам создавать сложные и интересные визуальные элементы с минимальными усилияи и являются действительно мощным инструментом для любого веб-разработчика.