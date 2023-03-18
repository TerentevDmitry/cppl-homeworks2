# �������� ������� � ������� ���� �������: ���������� � ��������

�������� ��� �������, �� ������� ������������� ������ ���������� � �������� � ����� ���������� � �� ������ ������� ������ ����������� :) 

### ���� �������

1. ��������� �������� � ���������� ������ � ����������.
2. ����� ���������������� ��� ������.

### ���������� � ���������� ��������� �������

1. ��� ���������� ������� � ����������� ����� ����� ��������� � ������������ �������� Windows ��� macOS � ������������� �� ��� Microsoft Visual Studio 2022, ������� ��� ���������� ���������� �������� �� C++.
2. ������� �� [GitHub](https://github.com/). [���������� �� ����������� �� GitHub](https://github.com/netology-code/cppm-homeworks/tree/main/common/sign%20up).
3. ������� �������� ������ [Git](https://git-scm.com/), ������������� ��������. [���������� �� ��������� Git](https://github.com/netology-code/cppm-homeworks/tree/main/common/download).

### ���������� �� ���������� ��������� �������

[���������� ���� �� ������](https://github.com/netology-code/cppm-homeworks/blob/main/common/readme.md).

------

### ������� 1

[��������� � ��������](https://github.com/netology-code/cppl-homeworks/tree/main/02/01).
<details>
# ������ 1. ��������� � ��������

### ��������
������� ������ � ���������. ���������, ����� ��������� ��������������� � �������� ���������� ���������.

### ��� ��������� 

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

### ������ ���������� ������ ���������
```
x:0, y: 0
x:1, y: 2
x:2, y: 4
x:3, y: 6
x:4, y: 8
```



</details>

### ������� 2*

[�������� ������](https://github.com/netology-code/cppl-homeworks/tree/main/02/02).

------

### ������� ����� �������� ������

����� ����� �������� �������, ���������� � ������ �������� ������ �� ��� �����������.

### �������� ������ �������� ������

1. � ������ �������� ����������� ������ �� ����������� � ����� ��� ������� 1 (2, ���� �������).
2. � ������ ���������� ���, ������� ��� ������� ��������� ��������� � ������� ��������.





