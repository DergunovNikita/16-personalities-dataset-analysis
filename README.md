# 16-personalities-dataset-analysis


В этой работе были проведены исследование различных признаков из датасета, их анализ, визуализация данных по признакам, проведены тесты на проверку гипотез с помощью t-тество и теста Xi-2. Затем построена модель прогнозирования результатов через модель случайного леса.


Описание признаков:

**Age** - возраст опрошенного (количественный)

**Gender** - пол опрошенного (номинальный)

**Education** - бинарная переменная: высшее образование или выше (1); неполное высшее или ниже (0) (номинальный)

**Introversion Score** - Непрерывная переменная от 0 до 10, представляющая тенденцию опрошенного к интроверсии против экстраверсии. Более высокие оценки указывают на большую склонность к экстраверсии (количественный)

**Sensing Score** - Непрерывная переменная от 0 до 10, представляющая предпочтение опрошенного к аналитическим решениям по сравнению с интуицией. Более высокие оценки указывают на предпочтение аналитики. (количественный)

**Thinking Score** - Непрерывная переменная от 0 до 10, указывающая на индивидуальное предпочтение к объективному принятию решений по сравнению с субъективным. Более высокие оценки указывают на предпочтение принятий решений объективно (количественный)

**Judging Score** - Непрерывная переменная от 0 до 10, представляющая предпочтение индивидуума по отношению к планированию или спонтанному принятию решений. Более высокие оценки указывают на предпочтение в составлении планов (количественный)

**Interest** - основная сфера интереса опрошенного (номинальный)

**Personality** - тип личности опрошенного (исследуемая переменная, номинальный)

