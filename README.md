# MIPS-simple-conflict
This is a simple tool to create 8 kinds of  conflicts  which  between the two instruction.

1.这是处理一阶数据相关的程序。

2.什么是一阶数据相关？ 

一阶数据相关:第I条指令的源操作寄存器与第[I-1]条指令（即上一条指令）的（EX冒险）目标寄存器相重，导致的数据相关称之为一阶数据相关。

3.主要通过以下十个函数分别实现，具体可以参考代码注释。

void CreateR_R();

void CreateR_I();

void CreateR_R_And_R_I();

void CreateR_I_And_R_R();

void CreateLoad_And_R_R();

void Load_Select(int a);

void CreateLoad_And_R_I();

void CreateR_I_And_Store();

void Store_Select(int a);

void CreateR_R_And_Store()
