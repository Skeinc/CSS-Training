# CSS Buttons

Кнопки - это важный элемент интерфейса, с которым пользователи взаимодействуют чаще всего. CSS предоставляет множество возможностей для стилизации кнопок, чтобы они не только выглядели привлекательно, но и были удобные в использовании.

## Базовая стилизация кнопок

Начнем с создания базового стиля для кнопок. CSS позволяет настроить цвет, размеры, отступы, закругления и многое другое.

```
<button type="button" class="basic-button">Click</button>
```

```
.basic-button {
    width: auto;
    height: 50px;
    appearance: none;
    outline: none;
    border: none;
    background-color: #4CAF50;
    color: white;
    font-size: 16px;
    padding: 0px 32px;
    border-radius: 4px;
    cursor: pointer;
    transition: all 0.3s ease;
}
```

Этот стиль создает простую и аккуратную кнопку с зеленым фоном и белым текстом. ``border-radius`` добавлять легкие закругления углов, что делает ее более современной.

## Эффект наведения (hover)

Чтобы кнопка была интерактивной, можно добавить стилизацию при наведении:

```
&:hover {
   border-radius: 10px; 
}
```

## Переходы (Transitions)

Плавные переходы делают кнопку более интерактивной и привлекающей внимание. Для осуществления данного функционал необходимо добавить CSS свойство ``transition``.

```
transition: all 0.3s ease;
```

## Кнопки с тенью (Box shadow)

Тень добавляет глубину и объема кнопке. CSS свойство ``box-shadow`` позволяет настраивать тень:

```
&:hover {
    border-radius: 10px; 
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2)
}
```

## Эффект при нажатии

Чтобы кнопка визуально "подгружалась" при нажатии, уменьшите тень:

```
&:active {
    transform: scale(1.1);
}
```

## Круглые кнопки

С помощью свойства ``border-radius`` можно создать круглые кнопки, применив большое значение к радиусу углов.

```
.round-button {
    width: auto;
    height: 50px;
    appearance: none;
    outline: none;
    border: none;
    background-color: #4CAF50;
    color: white;
    font-size: 16px;
    padding: 0px 32px;
    border-radius: 50%;
    cursor: pointer;
    transition: all 0.3s ease;

    &:hover {
        border-radius: 25%; 
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2)
    }

    &:active {
        transform: scale(1.1);
    }
}
```

## Кнопки с градиентом

Градиенты делают кнопки более выразительными. Добавьте ``background`` с градиентом, чтобы создать красивый визуальный эффект:

```
.gradient-button {
    width: auto;
    height: 50px;
    appearance: none;
    outline: none;
    border: none;
    background: linear-gradient(45deg, #f06, #f90);
    color: white;
    font-size: 16px;
    padding: 0px 32px;
    border-radius: 4px;
    cursor: pointer;
    transition: all 0.3s ease;

    &:hover {
        border-radius: 10px; 
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        background: linear-gradient(45deg, #f90, #f06);
    }

    &:active {
        transform: scale(1.1);
    }
}
```

## Иконки на кнопках

Иконки на кнопках повышают удобство и визуальную привлекательность. С помощью HTML можно легко добавиь иконку рядом с текстом кнопки.

## Плавающие кнопки

Плавающие кнопки популярны в мобильных интерфейсах. Они фиксируются на странице и используются для важных действий.

## Заключение

CSS позволяет создавать кнопки любой сложности и стиля. Вы можете добавлять эффекты наведения, плавные переходы, тени, градиенты и анимации, чтобы сделать кнопки более привлекательными. Также с помощью CSS-переменных можно упростить стилизацию кнопок и сделать ее более гибкой.