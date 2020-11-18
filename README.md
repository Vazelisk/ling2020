# Программирование и теория алгоритмов на ФиКЛ, 3 курс

## Команда курса и важные ссылочки

Преподаватели:

* Егор Соловьев (телеграм @esolovev, почта egorsolovev@gmail.com)
* Елена Захарова (телеграм @thislena, почта 1583253@gmail.com)
* Олег Сериков (телеграм @oserikov, почта srkvoa@gmail.com)

Ассистенты:

* Марк Рофин (телеграм @Broccoliman)
* Сергей Юхатсков (телеграм @uhnsa)

Канал курса в телеграме (по кнопке Discuss открывается чат): https://t.me/joinchat/AAAAAEymnR1mrd2li16QjA


Табличка с оценками: TODO

Анонимная форма для предложений по курсу: https://forms.gle/hX9Uxq7mK2bXo5Tt5

## План занятий

(может незначительно меняться в процессе курса)

### 2 модуль
| Номер  | Преподаватель  | Дата  | Тема  | Материалы |
|---|---|---|---|---|
| 01  | Егор  | 28.10.2020 9:30  | Функции и области видимости, встроенные типы данных, модули и пространство имен. Передача аргументов в функцию. | [Тетрадка](https://github.com/esolovev/ling2020/blob/main/lectures/01.ipynb), [тетрадка после семинара](https://github.com/esolovev/ling2020/blob/main/lectures/01_done.ipynb), видео ([часть 1](https://drive.google.com/file/d/1QAPgeZOhrxD6_cUgz8XiZnAkai-YTB5A/view?usp=sharing), [часть 2](https://drive.google.com/file/d/1vIe0r498J2Gc3knR0lJtauf1SaypiERy/view?usp=sharing)) |
| 02  | Егор  | 02.11.2020 14:40 (в зуме) |  Теория алгоритмов. Вычислительная модель. Языки программирования.  | [Слайды](https://github.com/esolovev/ling2020/blob/main/lectures/02.pdf), видео ([часть 1](https://drive.google.com/file/d/1atxUArAZsk9PcDD9dr7JAAueQqbKMZPH/view?usp=sharing), [часть 2](https://drive.google.com/file/d/1252X6rILwbzpP3eW7fyWLT1u_8hhH_4s/view?usp=sharing))
| 03 | Олег | 06.11.2020 11:10 | Linux, bash и их друзья. | [видео](https://drive.google.com/file/d/1kwOAIbPlaBL6pHYInCw_Opj2ZAD2gwMj/view?usp=sharing)
| 04 | Олег | 09.11.2020 14:40 (в зуме) | Задача сортировки массива. Наивные и квадратичные алгоритмы сортировки. Сложность алгоритмов. Устойчивость сортировок и дополнительные затраты на память. | 
| 05 | Олег | 11.11.2020 9:30 | Linux, bash и их друзья. | 
| 06 | Олег | 13.11.2020 11:10 | Задача сортировки массива. Наивные и квадратичные алгоритмы сортировки. Сложность алгоритмов. Устойчивость сортировок и дополнительные затраты на память. |
| 07 | Егор | 18.11.2020 9:30 | Декораторы |
| 08 | Олег | 20.11.2020 11:10 | Принцип «разделяй и властвуй». Сортировка слиянием. Быстрая сортировка. Бинарный поиск. |
| 09 | Лена | 25.11.2020 9:30 | Класс, объект. Конструктор и деструктор. |
| 10 | Олег | TBA | Принцип «разделяй и властвуй». Сортировка слиянием. Быстрая сортировка. Бинарный поиск. |
| 11 | Лена | TBA | Композиция и агрегация. Абстракция данных, инкапсуляция, наследование, полиморфизм.|
| 12 | Олег | TBA | Принцип «разделяй и властвуй». Сортировка слиянием. Быстрая сортировка. Бинарный поиск. |
| 13 | Лена | TBA | Класс, объект. Конструктор и деструктор. Композиция и агрегация. Абстракция данных, инкапсуляция, наследование, полиморфизм.|
| 14 | Егор | TBA | Абстрактный тип данных. Очередь, стек, связный список, массив, очередь с приоритетом. |
| 15 | Лена | TBA | Класс, объект. Конструктор и деструктор. Композиция и агрегация. Абстракция данных, инкапсуляция, наследование, полиморфизм.|
| 16 | Егор | TBA | Абстрактный тип данных. Очередь, стек, связный список, массив, очередь с приоритетом. |
| 17 | Лена | TBA | Перегрузка операторов. Исключения.|
| 18 | Егор | TBA | Абстрактный тип данных. Очередь, стек, связный список, массив, очередь с приоритетом. |
| 19 | Лена | TBA | Перегрузка операторов. Исключения.|
| 20 | Егор | TBA | Ассоциативный массив. Хэш-таблицы, словари, множества.|
| 21 | Лена | TBA | Итераторы и генераторы. Абстрактные классы. Статические методы и методы классов (модуль abc). |
| 22 | Егор | TBA | Ассоциативный массив. Хэш-таблицы, словари, множества.|
| 23 | Лена | TBA | Итераторы и генераторы. Абстрактные классы. Статические методы и методы классов (модуль abc). |


### 3 модуль

* Ассоциативный массив. Хэш-таблицы, словари, множества. Модуль collections в Python.
* Юнит-тесты: как и зачем писать. Mock. Coverage.
* Графы. Базовые алгоритмы на графах: поиск в глубину, поиск в ширину; алгоритм Дейкстры; топологическая сортировка; алгоритм Прима (модуль networkx). 
* Жадные алгоритмы.
* Основы матричной алгебры. Матричные разложения. Методы оптимизации. Машинное обучение. Градиентный спуск.
* Обучение на размеченных данных. Признаки в машинном обучении. Первичная обработка данных.
* Линейные модели. Линейная классификация.
* Отбор признаков.
* Метрики качества. Кросс-валидация. Многоклассовая классификация, несбалансированные данные.
* SQL.
* Многопоточность в Python и вообще.


### 4 модуль

* Проблема переобучения, регуляризация
* Метод ближайших соседей
* Решающие деревья
* Ансамбли. Бэггинг
* Алгоритмы кластеризации
* Методы понижения размерности
* Векторизация текстов. Count, tf-idf
* Векторизация текстов. Эмбединги

## Домашние задания

TODO


## Оценивание

Полная программа дисциплины доступна [тут](https://docs.google.com/document/d/1_h-Stvkk6zwTyXq5uUuqyTheJ6kxLV26OAdGrC6Gu-8/edit?usp=sharing).

Предусмотрены:

1) контрольная работа по объектно-ориентированному программированию на Python
2) домашние работы несколько раз в модуль
3) устный коллоквиум по машинному обучению
4) индивидуальный или групповой проект с последующей устной защитой (в том числе по смежным темам, не рассмотренных в основной части курса)
5) экзамен в конце курса, проводится в устной или письменной форме на усмотрение преподавателей

Промежуточные оценки (оценки за контрольную работу / коллоквиум, средние арифметические оценок за домашние работы, оценка за проект) не округляются.



Итоговая оценка = 0.12[коллоквиум] + 0.12[контрольная работа] + 0.11[проект] + 0.1[домашнее задание 2] + 0.2[домашнее задание 34] + 0.35[экзамен]

Если округленная по стандартным правилам итоговая оценка больше 10, она считается равной 10.

Здесь [домашнее задание 2] - среднее арифметическое оценок за ДЗ во 2 модуле, [домашнее задание 34] - среднее арифметическое оценок за ДЗ в 3-4 модулях.

**Правила получения автомата**

Определим накопленную оценку как 0.2[коллоквиум] + 0.2[контрольная работа] + 0.2[проект] + 0.16[домашнее задание 2] + 0.34[домашнее задание 34].

Если накопленная оценка после округления по стандартным правилам получается >= 4, студент имеет право получить её в качестве оценки за экзамен.


