# Алгоритмы и структуры данных (С++), 2020 г.

Программный код с лекций по информатике Хирьянова Т.Ф.
на ФТШ ЛФИ МФТИ (ФОПФ) в 2020 году.

Лицензия на материалы курса: ![Attribution ShareAlike CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)

Сайт курса: http://cs.mipt.ru/cpp_algo

## Рабочая программа дисциплины "Информатика":

по дисциплине: Информатика
по направлению: 03.03.01 «Прикладные математика и физика»
физтех-школа:	ЛФИ
кафедра:	информатики и вычислительной математики
курс:	1
семестр:	2

Трудоёмкость:
- лекции – 30 часов
- лабораторные занятия – 60 часов
- самостоятельная работа – 90 часов

ВСЕГО АУДИТОРНЫХ ЧАСОВ – 90

Программу и задание составил:	ст. преп. Т.Ф. Хирьянов

### Тематический план семестра

1. Ввод-вывод, ветвления и циклы. Однопроходные алгоритмы. Структура простой программы. Переменные С++: необходимость объявления, строгость типизации, присваивание. Ввод-вывод в std:: потоки cin, cout, cerr. Арифметические операции +, -, \*, /. Операторы сравнения <, <=, ==, !=. Описание простых функций. Cинхронный вызов и возврат по стеку вызовов. Метки и goto. Доводы против оператора goto Эдсгера Дейкстры. Оператор for. Генерация арифметической и геометрической прогрессий. Оператор if. Фильтрация потока чисел. Оператор while. Алгоритм Евклида на С++. Вложенные и каскадные условные конструкции. Обработка последовательностей: подсчёт, сумма, произведение, поиск максимального. Инициализация переменной при поиске максимума и минимума.
2. Целый и логический типы. Алгоритмы полного перебора. Двоичное представление данных. Двоичное кодирование. Двоичная СС и кольца вычетов. Знаковые целые: дополнительный код. Целочисленные типы С++11: intN_t. Явное приведение типа. Битовые операции с целыми: сдвиги, наложение маски. Обмен переменных значениями: универсальный и через XOR. Остаток при делении нацело: %. Разложение числа на цифры. Логический тип bool. Операции !, &&, ||, ^ и , not, and, or, xor. Индуктивные функции: поиск числа, проверка критерия. Алгоритмы полного перебора. Тест простоты числа с использованием переменной-флага. Разложение числа на множители. Управление циклом: break, continue. Определение типа struct. Функция sizeof().
3. Плавающая точка. Математические методы. Представление вещественных чисел в памяти ПК. Cтандарт IEEE 754-2008. Типы чисел с плавающей точкой в С++ и их соответствие стандарту. Арифметика чисел с плавающей запятой (точкой). Ошибки вычислений. Машинная точность. Иерархия типов чисел в С++. Неявное приведение типа. «Грабли»: приоритет беззнаковых, деление целых. Список всех операций С++ с приоритетами. Модуль cmath. Математические функции С++: выражение аналитических функций. Суммирования ряда Тейлора. Численное интегрирование. Бисекция. Поиск корня уравнения методом двоичного поиска.
4. Одномерные массивы. Адреса и указатели. Массивы в С++. Хранение в памяти. Фиксированный размер и однотипность элементов. Скорость доступа к элементам. Решето Эратосфена. Копирование массива. Копирование с реверсом. Реверс массива и циклический сдвиг. Добавление и удаление элемента в конце и в начале массива. Стек, очередь и дек на массиве. Адреса и указатели в С++. Размер ячейки для хранения адреса. Разыменование * и взятие адреса &. Адресная арифметика в С++. Преобразование типа указателя. Тип void*. Реинтерпретация данных. Массивы структур struct и структура struct, содержащая массив. Проверка корректности скобочной последовательности.
5. Универсальные сортировки O(N2). Сортировка массива: постановка задачи. Сортировка обезьяны (без реализации). Проверка упорядоченности за O(N). Сортировка дурака. Сортировка методом пузырька. Сортировка вставками. Сортировка выбором. Устойчивость сортировок.
6. Связные списки. Динамическая память. Выделение и освобождение динамической памяти: malloc(), calloc(), free(). Операторы new и delete. Ошибки работы с памятью. Контроль за динамической памятью. Некорректные адреса. Инициализация указателей: NULL и nullptr. Создание одномерного динамического массива. Реаллокация в памяти для динамического расширения массива. Списки: односвязный, двусвязный, кольцо. Асимптотика связных списков для разных задач. Стек на односвязном списке. Дек на двусвязном списке.
7. Двумерные массивы. Обычные двумерные массивы в С++. Заполнение двумерного массива. Треугольник Паскаля. Транспонирование матрицы. Умножение матриц. Динамические двумерные массивы в С++. Линеаризация двумерного массива вручную. Функции. Синхронный вызов. Возврат по стеку вызовов. Сегмент STACK и передача параметров по значению. Модель памяти приложения. Локальные и глобальные переменные. Передача массива в функцию и возврат из функции в С++. Проблема ответственности за освобождение памяти.
8. Бинпоиск и спецсортировки. Линейный поиск в массиве. Бинарный поиск в упорядоченном массиве. Сортировка подсчётом. Поразрядная сортировка.
9. Рекурсия. Метод ветвей и границ. Прямой и обратный ход рекурсии. Факториал числа. Алгоритм Евклида. Быстрое возведение в степень. Вычисление чисел Фибоначчи. Ханойские башни. Рекурсивная генерация всех чисел длины M. Генерация всех перестановок в массиве. Перебор с возвратом: метод ветвей и границ.
10. Быстрые сортировки. Принцип «Разделяй и властвуй». Умножение Карацубы. Быстрая сортировка Тони Хоара. Сортировка слиянием.
11. Динамическое программирование. Количество траекторий на схеме дорог. Проблема повторных вычислений на примере чисел Фибоначчи. Динамическое программирование сверху и снизу. Кузнечик: количество траекторий, траектория минимальной стоимости.
12. Двумерное динамическое программирование. Алгоритм укладки рюкзака (дискретный). Наибольшая общая подпоследовательность. Наибольшая возрастающая подпоследовательность.
13. Строки и работа с файлами. Кодировки символов: ASCII, однобайтные и семейство Unicode. Строка как массив символов. Си-строки и ANSI-строки. Почему Си-строки не следует использовать для обработки текста. Проверка равенства строк. Простой и вероятностный алгоритмы. Вычисление расстояния Левенштейна. Поиск последовательности редакционных изменений. Работа с файлами в чистом Си. Два уровня API.
14. Поиск подстрок. С++ строки std::string. Поиск подстроки: наивный алгоритм. Префикс-функция. Алгоритм Кнута-Морриса-Пратта. Z-функция и Z-алгоритм. Работа с потоками ifstream, ofstream, fstream. Форматирование ввода-вывода: iomanip.
15. Параллелизм на системах с общей памятью. Ресурс параллельности. Потоки. Асинхронные вызовы.
16. _
17. _
18. _
19. _
20. Лекция 5 (осень): Хеш-таблицы https://www.youtube.com/live/Tui85_T4qdA?feature=share (без кода С++)


### Методические указания обучающимся

Ваша цель — запомнить классические алгоритмы и структуры данных, знать их асимптотическую сложность, уметь их описывать устно, а также программировать их на языке C++.
Курс содержит три вида учебной деятельности: 1) лекции, 2) лабораторные работы и 3) самостоятельная работа.

На лекциях по информатике излагается теория, разбираются алгоритмы с реализацией на C++. Посещение не обязательно, но пропуск лекций существенно усложняет выполнение лабораторных и домашних работ. Именно лекции задают содержательную линию учебного курса.

Описания лабораторных работ появляются по ходу семестра на сайте http://cs.mipt.ru/cpp_algo. Очное присутствие на лабораторных обязательно. Типичная работа представляет из себя: а) текст для изучения; б) упражнения; в) контест с автоматизированной системой проверки. Автоматически проверяемые задачи допускается доделывать дома в качестве самостоятельной работы. В самостоятельную работу включается также подготовка к сдаче устного зачёта. В течение семестра на лабораторных занятиях проводится 2 контрольные работы: промежуточная и итоговая.

### Оценивание

Дифференцированный зачёт сдаётся устно. Рекомендуемая итоговая оценка студента по предмету — это среднее арифметическое взвешенное оценок по лабораторным работам и контрольным.
Преподаватель, экзаменующий студента, видит все эти оценки по отдельности, а также рекомендуемую итоговую оценку. Исходя из ответа студента итоговая оценка в зачётку может быть отклонена от рекомендуемой на ±2 балла (по 10-балльной шкале).
Если преподаватель хочет повысить или понизить оценку на большее число баллов, он советуется со старшим преподавателем курса. Студент при несогласии с итоговой оценкой может потребовать апелляции у старшего преподавателя (в конце зачётной недели).
