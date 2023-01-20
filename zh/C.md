# 第二章

## 练习题
1.程序在编译时没有产生警告信息，编译完成后能正常运行。  
2.(a)该程序包含一个指令(#include)和四个语句(调用三次printf和调用一次return)  
(b)
```c
Parkinson's Law:
Work expands so as to fill the time
available for its completion.
```

3.
```c
#include <stdio.h>

int main(void)
{
  int height = 8, length = 12, width = 10, volume;

  volume = height * length * width;

  printf("Dimensions: %dx%dx%d\n", length, width, height);
  printf("Volume (cubic inches): %d\n", volume);
  printf("Dimensional weight (pounds): %d\n", (volume + 165) / 166);

  return 0;
}
```
4.
```c
#include <stdio.h>

int main(void)
{
  int i, j, k;
  float x, y, z;

  printf("Value of i: %d\n", i);
  printf("Value of j: %d\n", j);
  printf("Value of k: %d\n", k);

  printf("Value of x: %g\n", x);
  printf("Value of y: %g\n", y);
  printf("Value of z: %g\n", z);

  return 0;
}
```
5.(a)是不合法的，因为它是以数字开头  
6.这是一个关于编程惯例的问题。使用下划线是为了使代码更容易阅读和理解，多个相邻的下划线会使变量名称变得冗长不易于阅读和使用，所以没有必要使用多个下划线。  
7.(a)(e)  
8.这条语句有14个记号  
9.
```c
answere = ( 3 * q - p * p ) / 3;
```
10.在c语言中没有必要的空格。

## 编程题
[第二章编程题](https://github.com/eurislee/c_programming_a_modern_approach/tree/main/ch02/exercises)

# 第三章

## 练习题


## 编程题
