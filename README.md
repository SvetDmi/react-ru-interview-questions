## Вопросы на собеседовании React.js

Здесь собраны самые популярные вопросы, задаваемые на русскоязычных собеседованиях front-end разработчиков на React.js.  Тематика вопросов включает в себя как основы JavaScript так и глубокое понимание работы React.js.

**JavaScript**:

<details>
<summary>Какие типы данных существуют в JavaScript?</summary>
<div>
  <ul>
    <li>
      Число <b>«number»</b> - Единый тип число используется как для целых, так и для дробных чисел. Существуют специальные числовые значения Infinity (бесконечность) и NaN (ошибка вычислений). Например, бесконечность Infinity получается при делении на ноль. Ошибка вычислений NaN будет результатом некорректной математической операции.
    </li>
    <li>
      Строка <b>«string»</b>
    </li>
    <li>
      Булевый (логический) тип <b>«boolean»</b>
    </li>
    <li>
      Специальное значение <b>«null»</b> - В JavaScript null не является «ссылкой на несуществующий объект» или «нулевым указателем», как в некоторых других языках. Это просто специальное значение, которое имеет смысл «ничего» или «значение неизвестно».
    </li>
    <li>
       Специальное значение <b>«undefined»</b> - Значение undefined, как и null, образует свой собственный тип, состоящий из одного этого значения. Оно имеет смысл «значение не присвоено». Если переменная объявлена, но в неё ничего не записано, то её значение как раз и есть undefined.
    </li>
    <li>
      Объекты <b>«object»</b> - Первые 5 типов называют «примитивными». Особняком стоит шестой тип: «объекты». Он используется для коллекций данных и для объявления более сложных сущностей. Объявляются объекты при помощи фигурных скобок {...}
    </li>
  </ul>
  <p><i>Источник: <a href ="https://learn.javascript.ru/types-intro">learn.javascript.ru</a></i></p>
</div>
</details>

<details>
<summary>Что такое цикл событий (event loop) и как он работает?</summary>
<div>
  <p>Движок браузера выполняет JavaScript в одном потоке. Для потока выделяется область памяти — стэк, где хранятся фреймы (аргументы, локальные переменные) вызываемых функций.</p>
  <p>Список событий, подлежащих обработке формируют очередь событий. Когда стек освобождается, движок может обрабатывать событие из очереди. Координирование этого процесса и происходит в event loop.</p>
  <p>Это по сути бесконечный цикл, в котором выполняются многочисленные обработчики событий. Если очередь пустая — движок браузера ждет, когда поступит событие. Если непустая — первое в ней событие извлекается и его обработчик начинает выполняться. И так до бесконечности.</p>
   <img src="https://cdn-images-1.medium.com/max/1600/1*quyTIOs2hioCx1jRQ7-ojw.png" />
   <p><i>Источник: <a href ="https://medium.com/@pavelbely/javascript-event-loop-%D0%B2-%D0%BA%D0%B0%D1%80%D1%82%D0%B8%D0%BD%D0%BA%D0%B0%D1%85-%D1%87%D0%B0%D1%81%D1%82%D1%8C-1-a19e4d99f242">Pavel Bely, medium.com</a></i></p>
</div>
</details>
