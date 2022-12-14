### 最常见的15种命令行命令

| 命令                                    | 说明                                                         |
| --------------------------------------- | ------------------------------------------------------------ |
| pwd                                     | 查看当前所在目录                                             |
| ls                                      | 查看当前目录下的所有文件，简洁版                             |
| ls -a                                   | 显示所有文件及目录，包含隐藏文件                             |
| ls -l                                   | 功能：显示文件详细信息。<br />例子：-rw-r--r--.  1 root root  100 Dec 28  2013 .cshrc<br />第一列：<br />访问权限描述例子：-rw-r--r--。<br />第一个字符表示文件类型：-表示普通文件，d表示目录。<br />从第二个字符开始每三个一组。每组三个字符分别表示读(read)、写(write)、执行(execute)。第一组是文件拥有者权限。第二组为同一组下的用户权限。第三组为其他用户的用户权限。<br />第二列：链接数<br />第三列：拥有者<br />第四列：所属组<br />第五列：文件大小，单位字节<br />第六列：文件最后修改时间<br />第七列：文件名称。. 开头为隐藏文件。 |
| clear                                   | 清空屏幕                                                     |
| cd                                      | 修改目录。<br />空选项：跳转到用户根目录<br />cd 路径名: 跳转到制定路径名。 以/开头的路径表示绝对路径，不加表示相对路径。<br />cd .. :返回上一层目录<br />cd - : 返回到进入此目录之前所在的目录 |
| mkdir 新目录地址                        | 创建新目录<br />-p选项 若要创建的目录的上层目录未创建，那就一并创建上层目录 |
| touch 新文件                            | 创建一个新的文件                                             |
| cp 原始文件的路径 新拷贝文件的地址      | 复制文件                                                     |
| rm 要删除的文件<br />rm -r 要删除的目录 | 删除文件<br />删除目录                                       |
| nano 要编辑的文件                       | 内置的文本编辑器，比vim好用                                  |
| cat 文件1 文件2 ...                     | 连接文件或标准输入并打印。通常与重定向符使用。<br />cat file1 file2 > some_file 表示输出到文件<br />cat file1 file2 >> some_file 表示添加到文件末尾 |
| echo                                    | 用于打印和输出字符串。可以与重定向符配合使用                 |
| man                                     | 用于查看命令的帮助信息，例如man ls                           |
| apt-get                                 | Ubuntu、Debian的包管理工具<br />apt-get install 安装<br />apt-get remove 卸载<br />apt-get upgrade 升级<br />配合sudo apt-get ,提升到管理员权限。 |



### Reference

15+ Terminal Commands Every Developer Must Know ([https://www.youtube.com/watch?v=CV-ven_rxhw](https://www.youtube.com/watch?v=CV-ven_rxhw))
