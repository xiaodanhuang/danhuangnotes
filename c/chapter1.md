###C语言概述
#### chapter 1 初识C语言
此处省略好多个字
####chapter 2 C语言概述
#####include指令和头文件:
1. include <stdio.h>的作用相当于把stdio.h文件中的所有内容都输入该行所在的位置.include这行代码是一条C预处理器指令。通常，C编译器在编译前会对源代码做一些准备工作，即预处理
2. 在大多数情况下，头文件包含了编译器创建最终可执行程序要用到的信息。简而言之，头文件帮助编译器把你的程序正确地组合在一起。

#####main()函数
C程序一定从main()函数开始执行（目前不必考虑例外的情况）

#####注释
1. /\* 多行注释\*/
2. //单行注释

#####声明:所有变量都必须先声明才能使用
```
/*
1.在函数中有一个名为num的变量.
2.int表明num是一个整数
*/
int num

```
#####提高程序可读性的技巧
1. 在函数中用空行分隔概念上的多个部分。
2. 每条语句各占一行。

#####使用函数前先声明。