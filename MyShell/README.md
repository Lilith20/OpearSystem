## 自己设计的shell程序
### gcc shell.c -o shell
### ./shell 运行即可
实现的功能有：
1. 获取当前操作系统的用户名、当前路径、以及操作权限展示为提示符
2. 输入一系列的内部指令并执行：cd、exit、help以及无效指令
3. 输入一系列的外部指令并执行：ps、ls执行当前路径文件等
4. 利用管道标识符“||”将标识符的命令输出的内容作为标识符后面的命令的输入内容
5. 利用 < 和 >进行输入输出的重定向
6. 循环执行命令
