[TOC]

# 3. Java basic program design structure

Type | size
---|---
int | 4bytes
short | 2bytes
long | 8bytes
byte | 1byte
float | 4byte
double | 8byte

\u转义序列，转为Unicode表示的char

escape sequence | name
--- | --- 
\a | Bell (alert)
\b|Backspace
\f|Formfeed
\n|New line
\r|Carriage return
\t|Horizontal tab
\v|Vertical tab
\'|Single quotation mark
\"|Double quotation mark
\\|Backslash
\?|Literal question mark
\ ooo|ASCII character in octal notation
\x hh|ASCII character in hexadecimal notation
\x hhhh|Unicode character in hexadecimal notation if this escape sequence is used in a wide-character constant or a Unicode string literal.

## 普通类型转换与强制类型转换

低精度值可以直接转换为高精度值

```java
int n = 121376129;
float b = n;
```

高精度值强制转换为低精度则会有损失

```java
double x = 9.997
int nx = (int)x;//nx==9
```

## 位运算符

符号 | 意义
--- | ---
& | and
\| | or 
^ | xor(相同为0，相反为1) 
~ | not

 