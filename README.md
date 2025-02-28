# Проект 0. Угадай число
<a name="Оглавление"></a>

## Оглавление  
[1. Описание проекта](#Описание-проекта)

[2. Какой кейс решаем?](#Какой-кейс-решаем)  

[3. Краткая информация о данных](#Краткая-информация-о-данных) 

[4. Этапы работы над проектом](#Этапы-работы-над-проектом)  

[5. Результат](#Результат)    

[6. Выводы](#Выводы)

<a name="Описание проекта"></a>

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

[к оглавлению](#Оглавление)

<a name="Какой кейс решаем?  "></a>

### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

[к оглавлению](#Оглавление)


**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python

<a name="Краткая информация о данных"></a>

### Краткая информация о данных :
Данные в проекте целочисленные, чтобы научиться использовать numpy
  
[к оглавлению](#Оглавление)


<a name="Этапы работы над проектом "></a>

### Этапы работы над проектом :  

**Этап 1**

Написать проект в котором мы соревнуемся сначала с ботом, для понятия логики
соревнования ii vs human

**Этап 2**

Продолжить проект, где мы в рамках одной программы решаем один кейс
с угадываниям числа, внедряя уже numpy для решения кейса ii vs ii

**Этап 3**

Продолжить проект этапа 2, где происходит все тоже самое в рамках 
1000 итераций по заданому сиду, для отслеживания результата

**Этап 4**

Ппридумывания алгоритма, который за <20 итераций находил бы число 
и был понятен читающему код

**Пару слов**

В целом проект был готов на этапе выдачи задания, необходимо было только допискать код в .../guess-number-task/game_v2.py

[к оглавлению](#Оглавление)

<a name="Результаты"></a>

### Результаты:  
Результат работы программы в среднем за 8 попыток происходит угадывания числа

[к оглавлению](#Оглавление)

<a name="Выводы"></a>

### Выводы: 
В рамках ознакомительной работы, мы научились использовать numpy
для решения кейса по параметрам из [2. Какой кейс решаем?](#Какой-кейс-решаем) 
с условиями 

**Логика решения**
Необходимо найти максимум и минимум от заганного числа и назначить, каждый раз рандомно,
чтобы реализовывать уменьшение числового отрезка на котором необходимо найти число, которое
нам необходимо

[к оглавлению](#Оглавление)



Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️