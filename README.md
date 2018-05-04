运行快照:<br>
<img src="https://github.com/kabelyang/miniSqlite/blob/master/snapshot/screen.png">
可参照<a href='https://sqlite.org/cli.html'>https://sqlite.org/cli.html</a> 来输入sql命令测试。
<br><br>
该工程文件配置默认是可执行程序模式(.exe) 也可以将成静态库(.lib）或动态库模式(.dll)，<br>
在更改工程配置成库文件时，注意将shell.c 中的 <br>
#define MAKE_EXE   1  <br>
改为<br>
#define MAKE_EXE   0<br>

