---
tags:
  - Списки
  - Словники
---

# Основи Програмування
- [x] Визначення
- [x] Порівняння мов
    * [x] Табличка
    * [x] Короткий опис Python
    * [x] Історія Python
- [x] Текстові редактори


<div class="grid cards" markdown>

-   :material-text-short:{ .lg .middle }  __Визначення__

    ---

    Що таке Мова Програмування?

    [:octicons-arrow-right-24: Перейти](#programming-languages)

-   :material-select-compare:{ .lg .middle }  __Порівняння Мов__

    ---

    Які ще є мови і де вони кращі?

    [:octicons-arrow-right-24: Більше](#comparison)

-   :material-history:{ .lg .middle }  __Історія Python__

    ---

    Коротко про те як винайшли мову

    [:octicons-arrow-right-24: Читати](#python-history)

-   :material-toolbox:{ .lg .middle }  __Редактор Коду__

    ---

    Які інструменти знадобляться?

    [:octicons-arrow-right-24: Докладніше](#text-editors)

-   :fontawesome-solid-laptop-code:{ .lg .middle }  __Програмування__

    ---

    Що в основі Програмування?

    [:octicons-arrow-right-24: Перейти](#basics)

-   :material-calculator-variant:{ .lg .middle }  __Швидкий Калькулятор?__

    ---

    Комп'ютер - це просто швидкий калькулятор?

    [:octicons-arrow-right-24: Більше](#arithmetic-operators)

-   :simple-express:{ .lg .middle }  __Вираз та Твердження__

    ---

    Вирази (Значення) та Твердження (Результат)

    [:octicons-arrow-right-24: Читати](#expression-and-statement)

-   :material-invoice-import-outline:{ .lg .middle }  __Ввід\\Вивід__

    ---

    Звідки та куди?

    [:octicons-arrow-right-24: Докладніше](#input-and-output-aka-io)

-   :material-arrow-decision:{ .lg .middle }  __Рішення та Вибір__

    ---

    Так або Ні

    [:octicons-arrow-right-24: Читати](#decision)

-   :curly_loop:{ .lg .middle }  __Повторення, Цикли__

    ---

    Чому потрібно забути неповторність?

    [:octicons-arrow-right-24: Докладніше](#loops-and-repetition)


</div>
## Мови (Programming Languages)

???+ abstract "Визначення"
    **Мова програмування** - це набір ключових слів (переважно англійських), символів (дужки, коми, крапки, лапки, арифметичні знаки, спеціальні символи) які коли ==поєднуються у правильній== послідовності, можуть бути розпізнані інтерпретатором (чи компілятором) відповідної мови. Правильна (без синтаксичних помилок) програма може бути виконана. 
    
    Під час виконання програми (навіть правильної) можуть та _будуть_ виникати помилки, що є сигналом програмістові продовжувати вдосконалювати код. Професійні інженери програмного забезпечення {~~ніколи не~>_нерідко\_~~} допускають помилки.


## Порівняння мов (Comparison)

| Назва       | Сфера Застосування                             |
| :---------: | :----------------------------------------: |
| JavaScript  | Веб-сайти, Браузерні додатки, Фронтенд    |
| Java, C#    | Сервіси, Банкінг, Бекенд                  |
| C, C++      | Операційні Системи, Драйвери, Комп'ютерні Ігри| 
| Kotlin      | Android| 
| Swift       | iOS (iPhone)| 
| Bash        | Linux скрипти|
| **Python**  | Скрипти, Наука, Освіта, Бекенд, Фронтенд, Великі Дані| 

## Історія Python (History)
- Python має цікаву історію, яку не складно знайти в подробицях у інтернеті.
- Основним є те, що спочатку мову програмування написав один програміст.
- Після викладення коду Python в інтернет над його вдосконаленням почали працювати декілька, а згодом -- ==велика кількість цікавих та розумних людей== із різних куточків земної кулі.
- Впродовж кількох десятиліть мова вдосконалювалась, якісь частини ставали непотрібними та викидались із мови.
- Відносно недавно вийшла версія мови Python 3 яка продовжує рости та розвиватись. Додаються нові можливості, які відповідають на нові виклики.
- Таким чином мова еволюціонує, стає більш пристосованою до вимог сьогодення. 

## Текстові редактори (Text Editors)
Для редагування коду Python підходять будь-які ^^текстові^^ редактори. Редактори типу ~~Microsoft Word~~ не підходять, бо нам потрібен лише текст і буде заважати його форматування.


## Програмування (Basics)

Щоб перейти до розбору ідей програмування, давай спершу з'ясуємо що в нас є.

Є в нас небагато: ==Процесор==, ==Пам'ять==, пристрої ==Введення== та ==Виведення==.  
Але за допомогою ^^мов програмування^^ та ^^математичної логіки^^  
ми стільки всього навчились робити за допомогою _обмежених_ засобів!

## Артфметичні Дії (Arithmetic Operators)

:material-plus:{ .lg .middle } - Додавання  
:material-minus:{ .lg .middle } - Віднімання  
:material-multiplication:{ .lg .middle } - Множення  
:material-slash-forward:{ .lg .middle } - Ділення  
:material-multiplication:{ .middle }:material-multiplication:{.middle } - Піднесення до степеня

Операції виконуються в стандартному порядку для математики:

- Степінь
- Дужки
- Множення та Ділення
- Додавання та Віднімання

## Вираз та Твердження (Expression and Statement)

якщо ми пишемо `2 + 3` то на мові комп'ютера це має вигляд на зразок:

1. візьми число 2 і помісти в пам'ять
2. візьми число 3 і помісти в пам'ять
3. виконай операцію додавання

    В даному **алгоритмі** (послідовності) не вистачає

4. Візьми результат та помісти його в пам'ять. Поміть куди поклав результат за допомогою ==імені змінної==

Щоб результат не втратився, нам потрібно його якось назвати.  
Дати ^^ім'я змінній^^, використовуючи яке ми потім цей результат використаємо

`2 + 3` - це вираз (expression)  
Вираз може мати ==значення==. Значенням виразу `2 + 3` є число `5`  
  
`result = 2 + 3` - твердження (statement)  
Твердження може мати ^^результат^^. Результатом операції ^^присвоєння^^ є  

1. обчислення виразу справа від знака `=` (присвоїти)
2. присвоєння обчисленому значенню ім'я

## Введення та Виведення (Input and Output aka IO)

Пристрої Введення (**Input**):

- клавіатура
- миша
- контроллер
- веб-камера
- тач-пад
- сенсорний екран
- зчитувач штрих-кодів та QR-кодів

Пристрої Виведення (**Output**):

- екран
- принтер
- динаміки
- лампочки індикації
- вібро-привід
- проектор

Ми зосередимось на найпростіших з них - ==клавіатурі== та ==екрані==

Найпростішими джерелами вводу та цілями виводу інформації для нас будуть

1. Введення символів із клавіатури
2. Виведення символів на екран

## Розгалуження (Decision)

Коли програмі не доводиться робити вибір -- в ній відверто немає жодного сенсу.  
Тому ==приймати рішення== - це класичний функціонал всіх без виключення мов програмування.  

в загальному вигляді прийняття рішень виглядає так:
``` mermaid
graph LR
  A[Початок] --> B{Сталась Помилка?};
  B -->|Так| C[Хм...];
  C --> D[Відладка];
  D --> B;
  B ---->|Ні| E[Ура!];
```

Алгоритм такий:

1. Отримуємо вхідні дані
2. Формуємо питання Так\Ні
3. В залежності від отриманої відповіді виконуємо відповідний набір команд
4. Якщо є необхідність - повертаємось до перевірки умови.

Останній пункт дає нам поштовх у напрямку повторень та циклів.

## Цикли та Повторення (Loops and Repetition)

Якщо програма виконується один раз, то зі швидкістю :material-speedometer: сучасних процесорів :fontawesome-solid-microchip: виконання займало б лічені мілісекунди.  
Це свідчить про те, що є частина коду, що виконується багато разів чи навіть без кінця.  
  
Цикли - це конструкції мов програмування, які повторюють команду чи набір команд

1. Поки якась умова виконується (напр. "==Поки== є гроші в гаманці")
2. Поки не нарахована кількість повторень ("Рахую до 10")

Ось і все, що стосується Основ програмування. Далі подивимось як саме в Пайтон реалізовані ці ідеї.
