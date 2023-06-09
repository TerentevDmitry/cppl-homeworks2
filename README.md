# Домашнее задание к занятию «Под капотом: компиляция и линковка»

Выполнив это задание, вы сможете анализировать ошибки компиляции и линковки в своих программах и не будете бояться ошибок компилятора :) 

### Цель задания

1. Научиться находить и исправлять ошибки в программах.
2. Уметь классифицировать эти ошибки.

### Подготовка к выполнению домашнего задания

1. Для выполнения задания и прохождения курса нужен компьютер с операционной системой Windows или macOS и установленной на нём Microsoft Visual Studio 2022, готовой для разработки консольных программ на C++.
2. Аккаунт на [GitHub](https://github.com/). [Инструкция по регистрации на GitHub](https://github.com/netology-code/cppm-homeworks/tree/main/common/sign%20up).
3. Система контроля версий [Git](https://git-scm.com/), установленная локально. [Инструкция по установке Git](https://github.com/netology-code/cppm-homeworks/tree/main/common/download).

### Инструкция по выполнению домашнего задания

[Инструкция дана по ссылке](https://github.com/netology-code/cppm-homeworks/blob/main/common/readme.md).

------

### Задание 1

[Программа с ошибками](01).
<details>
# Задача 1. Программа с ошибками

### Описание
Найдите ошибки в программе. Добейтесь, чтобы программа компилировалась и выдавала корректный результат.

### Код программы 

``` C++
#include <iostream>
using namespace std; 

struct point {
	double m_x;
	double m_y;
	point(double x, double y) {
		m_x = x;
		y = y;
	}
}

void print_point(const point& point_object) {
	std::cout << "x:" << point_object.m_x << ", y: "
		<< point_object.m_y << std::endl;
}

int Main()
{
	int i;
	for (i = 0; i < 5; i++); {
		point my_point(i, 2 * i);
		print_point(my_point);
	}
	return 0;
}

void print_point(const point& point_object) {
	std::cout << "x:" << point_object.m_x << ", y: "
		<< point_object.m_y << std::endl;
}
```

### Пример правильной работы программы
```
x:0, y: 0
x:1, y: 2
x:2, y: 4
x:3, y: 6
x:4, y: 8
```


</details>


### Задание 2*

[Сплошные ошибки](https://github.com/netology-code/cppl-homeworks/tree/main/02/02).

<details>

# Задача 2*. Сплошные ошибки

### Описание
Придумайте по одной ошибке каждого типа: синтаксической, семантической и ошибке линковки.
Постарайтесь придумать ошибки, отличающиеся от представленных в лекции.

В комментариях перед кодом напишите тип ошибки, и как её исправить. 
</details>

------

### Правила приёма домашней работы

Чтобы сдать домашнее задание, прикрепите в личном кабинете ссылку на ваш репозиторий.

### Критерии оценки домашней работы

1. В личном кабинете прикреплена ссылка на репозиторий с кодом для задания 1 (2, если сделали).
2. В ссылке содержится код, который при запуске выполняет описанный в задании алгоритм.
