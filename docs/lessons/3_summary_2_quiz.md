---
tags:
  - Прості Типи
  - Рядки
---

# Уроки 1 та 2, ТЕСТ.

## Перша програма

<?quiz?>
question: Перша програма пишеться для того, щоб
answer-correct: перевірити процес запуску коду на виконання
answer: показати які круті програми можна писати
answer: здійснити обряд підключення до секретного клубу
content:
<div class="demo-highlight"><pre><span></span><span class="nv">def</span><span class="w"> </span><span class="nv">add</span><span class="ss">(</span><span class="nv">a</span>,<span class="w"> </span><span class="nv">b</span><span class="ss">)</span>:
<span class="w">    </span><span class="k">return</span><span class="w"> </span><span class="nv">a</span><span class="w"> </span><span class="o">+</span><span class="w"> </span><span class="nv">b</span>
</pre></div>
<style id="css-style">pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.demo-highlight .hll { background-color: #ffffcc }
.demo-highlight { background: #f8f8f8; }
.demo-highlight .c { color: #3D7B7B; font-style: italic } /* Comment */
.demo-highlight .err { border: 1px solid #F00 } /* Error */
.demo-highlight .k { color: #008000; font-weight: bold } /* Keyword */
.demo-highlight .o { color: #666 } /* Operator */
.demo-highlight .ch { color: #3D7B7B; font-style: italic } /* Comment.Hashbang */
.demo-highlight .cm { color: #3D7B7B; font-style: italic } /* Comment.Multiline */
.demo-highlight .cp { color: #9C6500 } /* Comment.Preproc */
.demo-highlight .cpf { color: #3D7B7B; font-style: italic } /* Comment.PreprocFile */
.demo-highlight .c1 { color: #3D7B7B; font-style: italic } /* Comment.Single */
.demo-highlight .cs { color: #3D7B7B; font-style: italic } /* Comment.Special */
.demo-highlight .gd { color: #A00000 } /* Generic.Deleted */
.demo-highlight .ge { font-style: italic } /* Generic.Emph */
.demo-highlight .ges { font-weight: bold; font-style: italic } /* Generic.EmphStrong */
.demo-highlight .gr { color: #E40000 } /* Generic.Error */
.demo-highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.demo-highlight .gi { color: #008400 } /* Generic.Inserted */
.demo-highlight .go { color: #717171 } /* Generic.Output */
.demo-highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.demo-highlight .gs { font-weight: bold } /* Generic.Strong */
.demo-highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.demo-highlight .gt { color: #04D } /* Generic.Traceback */
.demo-highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.demo-highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.demo-highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.demo-highlight .kp { color: #008000 } /* Keyword.Pseudo */
.demo-highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.demo-highlight .kt { color: #B00040 } /* Keyword.Type */
.demo-highlight .m { color: #666 } /* Literal.Number */
.demo-highlight .s { color: #BA2121 } /* Literal.String */
.demo-highlight .na { color: #687822 } /* Name.Attribute */
.demo-highlight .nb { color: #008000 } /* Name.Builtin */
.demo-highlight .nc { color: #00F; font-weight: bold } /* Name.Class */
.demo-highlight .no { color: #800 } /* Name.Constant */
.demo-highlight .nd { color: #A2F } /* Name.Decorator */
.demo-highlight .ni { color: #717171; font-weight: bold } /* Name.Entity */
.demo-highlight .ne { color: #CB3F38; font-weight: bold } /* Name.Exception */
.demo-highlight .nf { color: #00F } /* Name.Function */
.demo-highlight .nl { color: #767600 } /* Name.Label */
.demo-highlight .nn { color: #00F; font-weight: bold } /* Name.Namespace */
.demo-highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.demo-highlight .nv { color: #19177C } /* Name.Variable */
.demo-highlight .ow { color: #A2F; font-weight: bold } /* Operator.Word */
.demo-highlight .w { color: #BBB } /* Text.Whitespace */
.demo-highlight .mb { color: #666 } /* Literal.Number.Bin */
.demo-highlight .mf { color: #666 } /* Literal.Number.Float */
.demo-highlight .mh { color: #666 } /* Literal.Number.Hex */
.demo-highlight .mi { color: #666 } /* Literal.Number.Integer */
.demo-highlight .mo { color: #666 } /* Literal.Number.Oct */
.demo-highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.demo-highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.demo-highlight .sc { color: #BA2121 } /* Literal.String.Char */
.demo-highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.demo-highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.demo-highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.demo-highlight .se { color: #AA5D1F; font-weight: bold } /* Literal.String.Escape */
.demo-highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.demo-highlight .si { color: #A45A77; font-weight: bold } /* Literal.String.Interpol */
.demo-highlight .sx { color: #008000 } /* Literal.String.Other */
.demo-highlight .sr { color: #A45A77 } /* Literal.String.Regex */
.demo-highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.demo-highlight .ss { color: #19177C } /* Literal.String.Symbol */
.demo-highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.demo-highlight .fm { color: #00F } /* Name.Function.Magic */
.demo-highlight .vc { color: #19177C } /* Name.Variable.Class */
.demo-highlight .vg { color: #19177C } /* Name.Variable.Global */
.demo-highlight .vi { color: #19177C } /* Name.Variable.Instance */
.demo-highlight .vm { color: #19177C } /* Name.Variable.Magic */
.demo-highlight .il { color: #666 } /* Literal.Number.Integer.Long */</style>
<?/quiz?>

- Сам код першої програми роблять максимально простим
- Пайтон — чи не єдина мова, у якої найпростіша програма займає 1 простий рядок

## Функція print()

`print()` це функція яка виводить на екран те, що ми помістимо в круглі дужки.  
Наприклад:

- числовий літерал `5` або `123_456_789_000` або `3.14159265359`
- рядковий літерал `"Ukraine"`, `'Вистоїмо'` `"2025р"`
- числова змінна `e = 2,71828`
- рядкова змінна `s = "My name is "`
- будь–яка кількість цих або інших типів через кому `,`
- нічого
- f–рядок, спеціальний шаблон, що містить змінні або вирази `f"Два в степені 7 буде {2**7}"`

## f–рядок

Спеціальний тип рядків — f–рядок використовується, щоб поєднувати відомі та невідомі (змінні) значення.
Невідомі значення можуть бути отримані з різних джерел:

- від ОС (Операційної Системи),
- від користувача,
- від генератора випадкових чисел,
- з БД (Бази Даних) тощо  

???+ tip "Константи"
    Окремим випадком невідомих значень є константи. Константи вводять для того, щоб не міняти багато рядків коду.  
    Якщо наприклад зміниться параметр, який міняється доволі рідко.

## Змінні та присвоєння

- Пайтон робить процес створення змінних простим
- [Декларація та Визначення](2.md#declare-vs-definition) — терміни які треба знати
- Перший значить — заявити змінну (declare)
- Другий значить — надати значення (define)
- В мові Пайтон декларація відбувається в момент визначення (неявно)
- Тобто коли ви присвоюєте перше значення в цей самий момент змінна і виникає
- ==Присвоєння== — це коли ліворуч пишеться ==ім'я змінної==, потім знак `=` а за ним праворуч ==вираз або літерал==, значення, яке ми запишемо у змінну.

## input()

- Функція `input()` друкує запрошення до вводу та зчитує рячдок з клавіатури. Завершенням вводу є ++enter++
- `input()` повертає рядок, а значить
    1. ліворуч від `input()` має стояти якась змінна та `=`
    2. `input()` має бути в дужках іншої функції, бути параметром

## int()

- `int()` в дужках (на вході) може мати рядок, що схожий на ціле число `-123` або `1_000_000`
- `int()` може викликати помилку або повернути ціле число, а значить
    1. ліворуч від `int()` має стояти якась змінна та `=`
    2. `int()` має бути в дужках іншої функції, бути параметром

## Композиція функцій

=== "Без композиції"
    ```py title="Трішки простіше, але не так математично" linenums="1"
    age_str = input("Введіть свій вік: ")
    age_int = int(age_str)
    ```
=== "Використання композиції"
    ```py title="Компактно та елегантно" linenums="1"
    # int() — зовнішня функція input() — внутрішня  
    age = int(input("Введіть свій вік: "))
    ```

Ці 2 програми абсолютно ідентичні за ефектом, але виглядають трішки по–різному
