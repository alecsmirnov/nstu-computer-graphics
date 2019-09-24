# Лабораторные работы по дисциплине "Компьютерная графика" на факультете ПМИ, НГТУ


### Папки:
### 1. Введение в программирование с использованием OpenGL
> Разработать приложение, реализующие следующий пункты:
> 1. Отобразить в окне множество примитивов **GL_LINE_STRIP** (вершины которых задаются кликами мыши).
> 2. Для завершения текущего (активного) набора (множества) примитивов и начала нового зарезервировать специальную клавишу (пробел или 
правый клик мыши).
> 3. Для текущего набора примитивов представить возможность изменения цвета и координат его вершин.
> 4. Текущее множество примитивов выделять среди других.
> 5. Предусмотреть возможность удаления последнего примитива и последнего набора примитивов.
> 6. Продублировать команды в меню, созданном с помощью библиотеки GLUT.  
> 
> Дополнительные задачи:
> 1. Изменение не только координат и цвета вершин примитивов, но и режимов сглаживания, шаблона закрашивания примитива, … .
> 2. Изменение параметров (в том числе и удаление) не только текущего набора примитивов, но и произвольного.
> 3. Изменение параметров произвольного примитива в наборе.

### 2. Растеризация примитивов
> Разработать приложение, реализующие следующий пункты:
> 1. В соответствии с заданием отобразить объекты (правильные многоугольники), центр и «радиус» которых определяются кликами мыши.
> 2. Предоставить возможность изменять форму и положение объектов модельно-видовыми преобразованиями.
> 3. Предоставить возможность изменять цвет и текстуру текущего (активного) объекта.
> 4. Предоставить возможность включать и выключать логические операции смешивания цветов (в соответствии с вариантом задания).
> 5. Вывести на экране динамически меняемую крупную сетку условных пикселей и на ней растеризовать данные объекты в режимах «контур» и 
«с заполнением».
> 6. При растеризации пересекающихся объектов цвет области пересечения определять в соответствии с заданной операцией смешения цветов.
> 7. Продублировать команды в меню, созданном с помощью библиотеки GLUT.
>  
> | Объект                   | Логические операции |
> |:------------------------:|:-------------------:|
> | Правильный шестиугольник | AND + NOT AND       |

### 3. Вариант преподавателя 1
> Реализовать сцену с объектами типа "Сфера". Добавить функции смены освещения, выбора текстур и перемещения объектов.  

### 4. Трассировка лучей
> Разработать приложение, реализующие следующий пункты:
> 1. Считывать из файла (в зависимости от варианта):  
> а) тип объекта;  
> б) координаты и размер объектов;  
> в) параметры материала объектов.  
> 2. Выполнить трассировку первичных лучей.
> 3. Добавить зеркальную плоскость и учесть отраженные лучи.
> 4. Предусмотреть возможность включения/исключения объектов.
> 5. Предусмотреть возможность изменения положения источника света.
>  
> | Объекты №1 | Объекты №2           | Объекты №3          |
> |:----------:|:--------------------:|:-------------------:|
> | Сферы      | Прямоугольные призмы | Плоские поверхности |

### RGZ. Интерактивное создание кривых и поверхностей с использованием сплайнов
> Реализовать программу, отображающую график функции, получаемой в результате использования замкнутого **B-сплайна** переменной степени. 
>  
> Входными данными является набор точек на экране, задаваемый в произвольном порядке с помощью мыши. При добавлении новой точки сплайн должен автоматически перестраиваться.  
Программа должна предоставить возможность движения по сцене и масштабирования с помощью клавиатуры/мыши.  
Координатные оси и координатная сетка должны быть отображены и подписаны, причем при масштабировании размер ячеек сетки не должен меняться – меняются только числовые подписи и масштабируется сам график.  
В том случае, когда недостаточно контрольных точек для построения сплайна, следует выдавать соответствующее предупреждение, а сам сплайн, например, отображать ломаной.
