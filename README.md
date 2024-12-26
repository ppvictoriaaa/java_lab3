_**Автор**: Вікторія Пекур_

_**Група**: ІО-24_

_**Залікова книжка:** №2420_


**Лабораторна робота №2**

**Тема:** Анотації і рефлексія в Java

**Варіант:** 2420 % 3 = 2

**Опис програми:**

Програма виконує валідацію об'єктів класів Person, Car та Medicine з використанням двох підходів:

1) З рефлексією – перевірка полів об'єкта за допомогою рефлексії.


Кожен клас має аннотації для валідації полів, такі як:

1) @NotNull для перевірки на null

2) @StringLength для перевірки довжини рядка,

3) @MinValue і @MaxValue для перевірки значень числових полів.




**Висновок:**

Лабораторна робота продемонструвала два підходи до валідації об'єктів в Java: з рефлексією та без неї. Програма успішно перевіряє поля об'єктів класів `Person`, `Car` і `Medicine` за допомогою аннотацій. Валідація без рефлексії показала кращу продуктивність, хоча рефлексія є більш гнучким підходом. Програма коректно обробляє неправильні дані, виводячи відповідні помилки валідації.


