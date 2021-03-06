# Linux 基础命令行

### [参考文章](https://blog.csdn.net/u012104219/article/details/79125771)
1. **`Tab` 补全**
    + `Tab` 自动补全命令或文件名。
    + 未输入状态下连按2次 `Tab` 列出所有可用命令
    + 已输入部分命令名或文件名，按 `Tab` 进行自动补全。

1. **光标**
    + `up` 方向键上（可以调出输入历史执行记录，快速执行命令）
    + `down` 方向键下（配合 up 选择历史执行记录）
    + `Home` 移动光标到本行开头
    + `End` 移动光标到本行结尾
    + `PgUp` 向上翻页
    + `PaDN` 向下翻页
    + `Ctrl + C` 终止当前程序
    + `Ctrl + L` 清屏 = clear命令（记住这个快捷键，比clear高效很多）

1. **远程连接工具**
    + Xshell 5 （免费）
    + SecureCRT 6.6

1. **\* man, info, help** 
    + `man`命令：Linux 下的帮助指令，通过 man 指令可以查看 Linux 中的指令帮助、配置文件
      帮助和编程帮助等信息。
    + `info`命令：Linux 下 info 格式的帮助指令。就内容来说，info 页面比 man page 编写
      得要更好、更容易理解，也更友好，但 man page 使用起来确实要更容易得多。
    + `help`命令：用于显示 shell 内部命令的帮助信息。help 命令只能显示 shell 内部的命令
      帮助信息。而对于外部命令的帮助信息只能使用 man 或者 info 命令查看。


## Linux 基础命令行
1. **`cd` (change directory ): 切换工作目录至 dirname**
    + > Tip: cd directory-name: 文件名前不带 `/` 斜杠，和 windows 中不一样
    + `cd ~`  返回根目录 (进入用户主目录)
    + `cd ..`  返回上一级目录
    + `cd ../..` 返回上 2 级目录
    + `cd -` 返回进入此目录之前所在的目录

1. **`pwd` (print working directory)：以绝对路径的方式显示用户当前工作目录**
    + `cd` 用来切换目录，`pwd` 用来打印工作目录。    

1. **`ls` (list): 显示当前路径下的文件夹**
    + ls -a: 显示当前路径下的所有内容（包含隐藏文件）
    + ls -l: 显示详尽文件内容，包括权限、创建时间、文件大小等
    + ls -r: 以递归形式显示所有内容
    + ls -t: 以时间顺序显示，最新的在前面

1. **`mkdir`（）创建文件夹**

1. **`rmdir`: 删除空文件夹**

1. **`rm`: 删除文件**