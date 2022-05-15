#  Проекты (лабораторные)

## 1 курс
### Структуры и алгоритмы. Язык программирования Pascal

- Написание функций для вычисления натурального логарифма и квадратного корня через степенные ряды. 

-	Выполнить заполнение массива размера NxN значениями F(x) по спирали, начиная из центра, где Xi будут браться на заданном отрезке AB с равным шагом. Поменять местами min и max значения ячеек массива, в диагоналях, параллельных главной диагонали.

-	Дан текстовый файл, который содержит 3 программы на языке паскаль, которые гарантированно компилируются, начинаются со слова program, не содержат строк и комментариев. Найти программу с наибольшей вложенностью циклов и вывести её в отдельный файл.

-	Разработать пакет процедур для работы с динамической структурой данных.
Тип структуры данных: Упорядоченный по убыванию кольцевой односвязный линейный список с типом элемента integer. Повторяющиеся элементы не добавляются в список.

-	Разработать класс с процедурами для работы с фракталом множества Kантора. (отрисовка).

-	Считывание информации из текстовых файлов с разной структурой данных и составление документа на основе информации из файлов и данных пользователя (предметная область РЕМОНТ БЫТОВОЙ ТЕХНИКИ). Составление документа-отчёта по выполненной работе

## 2 курс
### Assembler

-	Арифметические и логические команды в ассемблере.
<br>GitHub: https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab1.1/AssemblerLab1.1.cpp
<br>https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab1.2/AssemblerLab1.2.cpp

-	Арифметические команды и команды переходов.
<br>GitHub: https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab2/AssemblerLab2.cpp

-	Программирование на языке ассемблер задач с использованием массивов строковых данных.
<br>GitHub: https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab3/AssemblerLab3.cpp

-	Работа с математическим сопроцессором в среде Assembler.
<br>GitHub: https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab4.1/AssemblerLab4.1.cpp
<br>https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab4.2/AssemblerLab4.2.cpp

-	Работа со строками в консоли на ассемблере (MASM).
<br>GitHub: https://github.com/BedPled/AssemblerLab/blob/main/AssemblerLab5/lab5.asm

### Алгоритмы и структуры данных. Язык программирования С++

-	Разработать пакет функций для работы (+, -, >, >=) с многоразрядными рациональными числами в шестнадцатеричной системе счисления.  
<br>Библиотеки: string, iostream, fstream.
<br>GitHub: https://github.com/BedPled/labaK2N1/blob/main/main.cpp

-	Реализация поиска подстроки в строке. Алгоритмы: линейный поиск, Бойера-Мура. 
<br>Библиотеки: string, iostream.

-	Реализация алгоритма сортировки. Алгоритмы: Сортировка вставками, Сортировка слиянием.
<br>Библиотеки: iostream.

-	Генерация множеств методом транспозиции соседних элементов.
<br>Библиотеки: iostream.

-	Реализация динамической Хэш таблицы и методов для работы с ней (состояние ячеек занята, удалена, свободная). 
<br>Библиотеки: iostream.

-	Разработка кольцевого дека и методов для работы с ним (статический на базе массива).
<br>Библиотеки: iostream, limits.h.
<br>GitHub: https://github.com/BedPled/RingDeque

-	Разработка своей реализации строк в виде односвязного списка блоков фиксированной длины и алгоритмов для работы с ними (копирование подстроки, удаление подстроки, поиск подстроки) 
<br>GitHub: https://github.com/BedPled/String



### С++

-	Шифрование и дешифрование алгоритмом Двойной перестановки.
<br>GitHub: https://github.com/BedPled/Crypto/blob/main/main.cpp

-	Транслитератор из кириллицы в латиницу. Без использования встроенных функций для строк. Работа с char*, преобразование ascii в utf-8. 
<br>Пример: "Привет, Ярик!" -> "Privet, Yarik!"
<br>GitHub: https://github.com/BedPled/translit

-	Реализовать алгоритм преобразования арифметического выражения, содержащего: ()/*+-0123456789 в ОПЗ, и калькулятор выражении
<br>Пример: “5 * (−3 + 8)” --> “5 3 − 8 + *” --> “25”
<br>GitHub: https://github.com/BedPled/OPZ-gtests

-	Определить собственный тип данных ComplexNumber
Перегрузить (overloading) функции сложения, вычитания, умножения, деления и вывода
<br>GitHub: https://github.com/BedPled/complex

-	Реализовать функции для кодирования и декодирования строки из/в base64
<br>Библиотеки: string
<br>GitHub: https://github.com/BedPled/base64

-	Считывание и обработка значений в одном потоке и с использованием многопоточности и сравнение времени. 
<br>Библиотеки: pthread, sstream, fstream, ctime.
<br>GitHub: https://github.com/BedPled/pthread

### ООП. Язык программирования С++

- Работа с наследованием классов.
<br>GitHub: https://github.com/BedPled/SimpleInheritance

- Работа с полиморфизмом.
<br>GitHub: https://github.com/BedPled/Polymorphism

- Работа с инкапсуляцией.
<br>GitHub: https://github.com/BedPled/Encapsulation/blob/main/main.cpp

- Итеративное написание класса с использоавнием принципов (low coupling, strong cohesion, SOLID, KISS, YAGNI, DRY и тд)
<br>GitHub: https://github.com/BedPled/StudentsPack/blob/main/main.cpp

- Предметная область Библиотека.
<br>Информационные объекты: Библиотека, Библиотекарь, Книги, Авторы, Посетитель
<br>Посетитель посещает библиотеку с целью найти книгу по имени автора И/ИЛИ по названию книги. Реализовать данный функционал, придерживаясь принципов DRY, KISS, YAGNI и Single Responsibility Principle
<br>GitHub: https://github.com/BedPled/Library/blob/master/main.cpp

- Реализация паттерна Factory Method
<br>GitHub: https://github.com/BedPled/Factory-Method/blob/main/main.cpp

- Реализация паттерна Builder
<br>GitHub:https://github.com/BedPled/Builder/blob/main/main.cpp

- Реализовать ОПЗ в ООП парадигме с соблюдением принципов DRY, YAGNI, KISS, SOLID с возможностью добавления новых операций
<br>GitHub: https://github.com/BedPled/OPZ-gtests

### Курсовая. Язык программирования Java
Алгоритм нечёткого поиска. Хэширование по сигнатуре. 
Анализ алгоритма поиска по сигнатуре в зависимости от способа построения сигнатуры (таблиц кодирования хэш функции)
<br>Описание алгоритма: Стр 10. https://cs.msu.ru/sites/cmc/files/docs/boycov.pdf 
<br>Фреймворк: JavaFX
Использрвал Сериализацию данных
<br>GitHub: https://github.com/BedPled/HashSignatureSearch


## 3 курс

### Алгоритмы и структуры данных (С++)
- Реализация шаблонного класса для работы с красно-чёрным деревом
<br>GitHub:  

- Реализация ориентированного графа в виде односвязного списка смежности с упорядоченным добавлением. 
<br>Алгоритм обхода вершин графа в глубину без дополнительной памяти.
<br>Алгоритм Форда, Мура и Беллмана.
<br>GitHub: https://github.com/BedPled/graph/blob/master/graph.h

### Современные интернет технологии (Frontend)

- Заверстать пользовательский интерфейс по типу современных мессенджеров (Telegram/Vk/WhatsApp). С помощью Javascript реализовать вывод добавляемых сообщений на экран.
<br>Page: https://bedpled.github.io/Messeger_like_UI/
<br>GitHub: https://github.com/BedPled/Messeger_like_UI

- Игра “Ударь крота”
<br>Page: https://bedpled.github.io/Whack-a-mole/
<br>GitHub: https://github.com/BedPled/Whack-a-mole

- Игра“Братья пилоты” с полем 4x4. Суть игры - закрасить все ячейки в другой цвет.
<br>Page: https://bedpled.github.io/Pilot-Refrigerator/
<br>GitHub: https://github.com/BedPled/Pilot-Refrigerator

- Обработка асинхронных событий с помощью JavaScript. Часы обратного отсчёта: минуты, секунды, миллисекунды.
<br>Page:https://bedpled.github.io/BombTimer/
<br>GitHub: https://github.com/BedPled/BombTimer

- Реализовать страницу-галерею с получением изображений под средством AJAX запросов с использованием Promise. 
<br>Page: https://bedpled.github.io/ArtStation/ (требует повторной перезагрузки для правильного отображения)
<br>GitHub: https://github.com/BedPled/ArtStation


### Java

- Работа с потоками
- Работа с БД

### Проектирование БД.

## Внеучебные проекты:

- Участиe в Siberian Game Jam на Unity (Язык программирования С#). Разработка аркадной игры за 48 часов.
<br> Суть игры: Машинка едет по дороге, объезжает препятствия, собирает бонусы. 
<br> Роль: геймдизайнер, программист. 

- Поисковые подсказки с ранжированием. Язык программирования Java 
<br>GitHub: https://github.com/BedPled/VKsearch


