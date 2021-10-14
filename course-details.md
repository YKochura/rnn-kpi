class: middle, center, title-slide 

# Рекурентні нейронні мережі обробки природної мови

Осінь, 2021

<br><br>
Кочура Юрій Петрович<br>
[iuriy.kochura@gmail.com](mailto:iuriy.kochura@gmail.com) <br>
<a href="https://t.me/y_kochura">@y_kochura</a> <br>


---

# Інструктор

Лекції
- Кочура Юрій Петрович
  - Кафедра ОТ, ФІОТ

<br>

.center[
.circle.width-40[![](figures/course-details/ykochura.jpg)]
]

---

class: middle

# Опис

Деталі

- Будуть розглянуті такі види архітектур рекурентних мереж: *one-to-one, one-to-many, many-to-one, many-to-many*
- Познайомитесь з задачами приктичного застосування цих архітектур


---


# Аудиторія

Цього семестру (Осінь 2021) заняття проходять онлайн в .bold[*BigBlueButton*] за посиланням:  [https://bbb.comsys.kpi.ua/b/yur-96u-ttq-eqe](https://bbb.comsys.kpi.ua/b/yur-96u-ttq-eqe)

.center.width-90[![](figures/course-details/bbb.png)]

---

class: middle 

# Матеріали лекцій

Матеріали лекцій розміщені за посиланням [https://github.com/YKochura/rnn-kpi](https://github.com/YKochura/rnn-kpi)

- Надається у HTML та PDF


.center.width-80[![](figures/course-details/github.png)]

---

class: middle

# Підручники - ГН

 Можливо, Вам стане в нагоді одна з цих книг, яка дасть Вам можливість більш детально ознайомитись з передовими темами глибинного навчання:

.smaller-xx.grid[
.kol-1-3[
[.center.width-80[![](figures/course-details/deep-learning-book-goodfellow-cover.jpg)]](https://www.deeplearningbook.org/)
.center[Безкоштовна -EN]
]

.kol-1-3[
[.center.width-95[![](figures/course-details/Neural-Networks-and-Deep-Learning.png)]](http://neuralnetworksanddeeplearning.com/index.html)
.center[Безкоштовна -EN]
]

.kol-1-3[
[.center.width-80[![](figures/course-details/deep-learning-with-python-second-edition-chollet.png)]](https://www.manning.com/books/deep-learning-with-python-second-edition?query=deep/)
.center[Безкоштовний перегляд -EN]
  ]
]

---

class: middle

# Підручники - РМ

 Деякі корисні матеріали, які можуть стати Вам у нагоді при опануванні рекурентних нейронних мереж для задач обробки природної мови:

.smaller-xx.grid[
.kol-1-2[
[.center.width-110[![](figures/course-details/SLP.png)]](https://web.stanford.edu/~jurafsky/slp3/)
.center[Безкоштовна -EN]
]

.kol-1-2[
[.center.width-120[![](figures/course-details/Jacob-Eisenstein-Natural-Language-Processing.png)]](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
.center[Безкоштовна -EN]
]

]

---


class: middle

# Обговорення

.smaller-xx[Усі оголошення та обговорення матеріалів лекцій здійснюватиметься в Telegram (повідомте мене, якщо Вас потрібно додати в цю групу)

- Задавайте питання, які Вас турбують. 
- Не соромтесь!
]

.center.width-25[![](figures/course-details/telegram.png)]

---


class: middle

# Оцінювання

- 20%  &nbsp;&emsp; Присутність на лекціях (10% кожна)
- 80%  &nbsp;&emsp; Залік (контрольна)
---

class: end-slide, center
count: false

.larger-xx[Почнемо!]