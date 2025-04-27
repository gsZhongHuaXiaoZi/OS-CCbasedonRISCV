# OS-CCbasedonRISCV

项目名称：{基于RISC-V的中文操作系统及C程序编译器的构建} 

项目链接：{本赛题在github上的链接：https://github.com/gsZhongHuaXiaoZi/OS-CCbasedonRISCV }

导师信息：{翟高寿，gszhai@bjtu.edu.cn }

难度：{高}

分类：{未归类操作系统内核、编程语言支持、界面设计、未归类运行时支持}

题目要求：

1、基于RISCV设计和构建简单的操作系统及C编译器；

2、操作系统支持自启动装入、特权级切换、多任务并发执行和中文显示，提供基本的系统调用接口和命令解释器以支持基本的文件编辑和命令执行处理；

3、C编译器支持在自己构建的操作系统中，能够编译至少如下两种类型的C程序和生成可执行文件，并在自制操作系统中正确运行。

C程序示例1：

#include <stdio.h>

int main(void)

{

 printf("Hello, OS World!\n");
 
}

C程序示例2：

#include <stdio.h>

int main(void)

{

 int zX, zY, zSum;
 
 printf("Please input 2 integers: X = ");
 
 scanf("%d", &zX);

 printf("Y = ");
 
 scanf("%d", &zY);
 
 zSum = zX + zY;
 
 printf(" X + Y = %d\n", zSum);
 
}

特征：{ C编译器其实涵盖了链接器的功能。printf和scanf以库函数方式实现，头文件stdio.h给出二者的函数原型声明。 }

预期目标：{ }

License：{ }

参考资料：{ }

备注：{ 微信群：riscv操作系统与C编译器 }
