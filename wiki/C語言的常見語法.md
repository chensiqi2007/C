# 參考網站及獲取幫助
[菜鳥教程](https://www.runoob.com/cprogramming/c-tutorial.html)

# 基礎語法
## 關鍵字

## 標識符

## 常量

## 字符串字面量

## 運算符
### 算數運算

| 運算符 | 描述               |
| :-: | ---------------- |
|  +  | 把兩個操作數相加         |
|  -  | 從第一個操作數中減去第二個操作數 |
|  *  | 把兩個操作數相乘         |
|  /  | 分子除以分母           |
|  %  | 取模運算符，整除後的餘數     |
| ++  | 自增運算符，整數值增加1     |
| --  | 自減運算符，整數值減少1     |

實例：
	#include <stdio.h>
	 int main() { 
	 int a = 21; 
	 int b = 10; 
	 int c ; 
	 c = a + b; 
	 printf("Line 1 - c 的值是 %d\n", c ); 
	 c = a - b; 
	 printf("Line 2 - c 的值是 %d\n", c ); 
	 c = a * b; printf("Line 3 - c 的值是 %d\n", c ); 
	 c = a / b; 
	 printf("Line 4 - c 的值是 %d\n", c ); 
	 c = a % b; 
	 printf("Line 5 - c 的值是 %d\n", c ); 
	 c = a++; 
	 // 赋值后再加 1 ，c 为 21，a 为 22 
	 printf("Line 6 - c 的值是 %d\n", c ); c = a--; 
	 // 赋值后再减 1 ，c 为 22 ，a 为 21 
	 printf("Line 7 - c 的值是 %d\n", c );

結果：
//《img》

<h4>a++與++a的區別</h4>
實例：
	#include <stdio.h>
	int main()
	{
	   int c;
	   int a = 10;
	   c = a++; 
	   printf("先赋值后运算：\n");
	   printf("Line 1 - c 的值是 %d\n", c );
	   printf("Line 2 - a 的值是 %d\n", a );
	   a = 10;
	   c = a--; 
	   printf("Line 3 - c 的值是 %d\n", c );
	   printf("Line 4 - a 的值是 %d\n", a );
	   printf("先运算后赋值：\n");
	   a = 10;
	   c = ++a; 
	   printf("Line 5 - c 的值是 %d\n", c );
	   printf("Line 6 - a 的值是 %d\n", a );
	   a = 10;
	   c = --a; 
	   printf("Line 7 - c 的值是 %d\n", c );
	   printf("Line 8 - a 的值是 %d\n", a );
	}

結果：
//《img》
### 關係運算符
| 運算符 | 描述 |
| :——: | :——: |
| == |  |
| != |  |
| > |  |
| < |  |
| >= |  |
| <= |  |

### 邏輯運算符

### 位運算符

### 賦值運算符

### 雜項運算符

## 分隔符