本工程是根据野火的教程创建的模板工程。

开发板：野火STM32F429挑战者V2

工程目录说明：

- Doc：用来存放程序说明的文件，由写程序的人添加
- Libraries：存放的是库文件
  - CMSIS：存放的是CMSIS的库文件
    - ins：头文件
    - src：源码文件
  - Driver：存放的是外设驱动的库文件
    - ins：头文件
    - src：源码文件
- Listing：存放编译器编译时候产生的 C/汇编/链接的列表清单
- Output：用来存放工程
- User：用户编写的驱动文件
  - ins：头文件
  - src：源码文件
- Project：存放工程文件
  - Keil：存放Keil工程文件
  - SourceInsight：存放SourceInsight工程的文件