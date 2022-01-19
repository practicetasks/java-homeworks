# Домашние задания по разделу «Java» - урок 1

### Описание
1. Просмотреть презентацию (урок 1 Java)
2. Просмотреть видео [ссылка](https://www.youtube.com/watch?v=5Jc9V0_zkIQ)
3. Прочитать статью (Базовый материал)
4. Выполнить задачи
5. Чтение книг

## Базовый материал:

### Насколько востребованы программисты?
Для начала посмотрим на сферу разработки в целом. Спрос на специалистов растёт от года к году. Вот несколько показательных фактов.
Сделаем сравнение с Россией. К 2027 году российскому рынку потребуется 2 миллиона айтишников [по данным исследования ФРИИ.](https://www.iidf.ru/upload/documents/Исследование%20ФРИИ%20Кадровый%20голод.pdf)
Ежемесячная динамика средних заработных плат в сфере IT значительно опережает динамику в сферах банковского дела, строительства, кадров и даже маркетинга и PR.

###  Какие термины помогут быстрее погрузиться в сферу
На всякий случай познакомимся с основными понятиями из сферы разработки. <br>
Мы не будем уходить в дебри и дадим только те термины, которые понадобятся для изучения нашего базового материала.  <br>

**Фронтенд** - Видимая пользователю сторона интерфейса: включает всё, что браузер выводит на экран пользователя, когда тот открывает веб-страницу.  <br>

**Бэкенд** - Скрытая от пользователя, программно-аппаратная часть сервиса: включает то, что работает на сервере и реализует логику работы сайта.  <br>

**Фулстек-разработчик** - Специалист, который разбирается во всём стеке технологий — работает и с фронтендом, и с бэкендом.  <br>

**QA** - Обеспечение качества итогового продукта (от англ. Quality assurance).  <br>

**Junior, Middle, Senior**  <br>
Обозначения уровня разработчика: **junior** — начинающий уровень, с опытом работы 1-1,5 года, **middle** — 2.5-3 года, **senior** — 5-6 лет. Ограничения по опыту очень условны: уровень зависит от навыков и компетенций. **Junior** — решает задачи под присмотром, **middle** — решает сам, **senior** — решает их самым оптимальным способом.
 
 ###  Какими бывают специалисты в IT:
**Направление:** Веб-разработка <br>
**Чем занимается:** Создаёт веб-приложения и сайты. Хорошая точка для старта: низкий порог входа, при желании можно дальше развиваться в других направлениях. <br>
**Варианты специализации:** <br>
Фронтенд-разработчик <br>
Бэкенд-разработчик <br>
Фулстек-разработчик

**Направление:** Мобильная разработка<br>
**Чем занимается:** Создаёт мобильные приложения. В мобильной разработке задачи сложнее, но зарплаты выше, а конкуренция ниже. <br>
**Варианты специализации:** <br> iOS-разработчик <br>
Android-разработчик

**Направление:** QA (тестирование) <br>
**Чем занимается:** Отвечает за качество того продукта, который делают программисты. Среди перечисленных профессий — это самый простой путь
в IT-сферу. <br>
**Варианты специализации:** <br> 
Ручное тестирование <br> 
Автоматизированное тестирование

**Направление:** 1С-разработка<br>
**Чем занимается:**  Написание конфигураций «с нуля»,  доработка типовых конфигураций 1С и администрирование, обновление типовых конфигураций 1С <br>
**Варианты специализации:** <br> 1С-разработчик <br>

**Направление:** Администрирование <br>
**Чем занимается:** Обеспечивает корректную работу IT-инфраструктуры (компьютерной техники, сетей и ПО) и информационной безопасности в организации. <br>
**Варианты специализации:** <br> Системный администратор <br>
Специалист по информационной безопасности

**Направление:** Разработка игр <br>
**Чем занимается:** Занимается созданием программного кода, визуализацией и концепцией игры <br>
**Варианты специализации:** <br>
Разработчик игр <br> 

## Задача 1
Какого типа переменные подойдут для хранения следующей информации:

Возраст человека; <br>
Население города; <br>
Число звезд в галактике; <br>
Средняя зарплата за год; <br>
Цвет фигуры; <br>
Длина в мм; <br>
Длина в см; <br>
Фамилия человека; <br>
Время года; <br>
Пол человека. <br>

Ответ на задачу необходимо написать текстом. Подумайте, какой тип данных лучше подойдет, какие операции в последующем будут совершаться, с какими другими типами данных будет взаимодействие. Зачастую тип переменной определяется исходя из конкретной задачи, в связи с чем он может значительно меняться. Порассуждайте, какие варианты могут подходить при разных условиях.

Пример ответа:
Возраст человека: Переменную с возрастом человека лучше сделать типа int. Можно выбрать дни, месяцы или годы. Например, для приложений, где будет использоваться возраст новорожденных, нужно использовать дни или месяцы. Для взрослых людей - годы.

## Задача 2

Задание 1. Дан фрагмент программы:
Какой тип данных нужно подставить вместо прочерка, чтобы программа работала корректно? Какой вывод в консоль вы получите?

```
_____ a = 120;
System.out.println(a - 20);
```
Задание 2. Дан фрагмент программы:
Какой тип данных нужно подставить вместо прочерка, чтобы программа работала корректно? Какой вывод в консоль вы получите?
```
_____ a = 2.5;
double b = a * 2;
System.out.println(b);
```
Задание 3. Дан фрагмент программы:
Какой тип данных нужно подставить вместо прочерка, чтобы программа работала корректно? Какой вывод в консоль вы получите?
```
_____ a = "Hello";
System.out.print(a + "World");
```
## Задача 3

Вы создаете приложение для учета работников компании. В нем есть данные о работнике: имя, фамилия, отчество, возраст, город. Создайте переменные и проинициализируйте их значениями. Поменяйте возраст сотрудника. Выведите все переменные в консоль (каждую с новой строки). Дайте комментарий к каждой строчке кода.

## Задача 4

Решим бухгалтерскую задачу. Каждый год бухгалтер получает информацию об изменении зарплат сотрудников, ему нужно провести расчеты. Известны зарплаты трех сотрудников:

1 сотрудник -- 55000 

2 сотрудник -- 40000

3 сотрудник -- 70000

Через месяц зарплата первого выросла в 2 раза, зарплата второго выросла на 15000, заплата третьего осталась без изменения. 

Реализуйте расчет новых сумм с помощью арифметических операций с присваиванием. Выведите новые суммы в консоль, каждую с новой строки.

#### Алгоритм выполнения для 4 задания:

1. Объявите 3 переменных, которые будут определять зарплату подчиненных на разных должностях;
2. Придумайте соответствующее название переменной и инициализируйте их размером заработной платы;
3. Выполните математические действия в соответствии с условием задачи;
4. Распечатайте полученный результат при помощи метода System.out.print(), каждый результат с новой строки.

#### Пример использования арифметической операции с присваиванием:

```java
lawyerSalary = lawyerSalary * 4;  // умножаем зарплату юриста на 4
```