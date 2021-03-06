# Инструкция по работе с Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо оформить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__.

Альтернативые способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**.

## Списки


Чтобы добаить ненумерованные списки, необходимо пункты выделить (*) или знаком (+). Например вот так:

* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить ненумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт
3. Третий пункт


## Работа с изоброжениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![картинка](IMG_5037.JPG)

## Ссылки

Чтобы вставить ссылку в текст, необходимо написать:
[Ссылка](https://gb.ru/lessons/238304)

## Работа с таблицами

Таблицы Markdown физически представлены с помощью тире (-) для разделения строки заголовка из содержимого и вертикальной черты (|) для столбцов. Пример:

Колонка | Символ
--------|--------
1       |   !
2       |   "  
3       |   #





## Цитаты
Для цитаты нужна только одна такая (>) скобка. Пример:
> Первая цитата
>> Вторая цитата
>>> Третья цитата
>>>> Четвертая цитата

## Экранирование
А что если эти символы нужны нам в самом тексте? Чтобы спецсимволы не исчезали и не влияли на оформление, нужно использовать экранирование. Как и во многих других языках программирования, этим целям служит обратная косая черта (бэкслеш).
Пример:

\*Нет курсива\* 

\*\*Нет жирного выделения\*\*


Исключение – когда надо вставить внутри кода грависы (обратные тики). Интерпретатор не посчитает их за обозначение инлайн-кода, если только весь участок кода заключен с двух сторон в двойные грависы.
