database image is malformed
############################

一直用得很好，但突然之间，下载课件到100%就失败，以前的课件也无法打开，系统提示 **database image is malformed**，怎么办？

这可能是您的用户数据文件损坏了，常见原因有磁盘空间不足，写入数据过程中突然掉电等。

试试这个办法：

1. 如果Aboboo正在运行，请退出Aboboo。

2. 找到 **我的文档\\Aboboo** ，重命名或者移动到别处。\
   **我的文档\\Aboboo\\udt\\audt.dat** 出错可能性较大, 可以试试只移动audt.dat或重命名。

3. 再次运行时，Aboboo会重建用户数据（一分钟内完成），重建后恢复正常。

4. 已损坏的用户数据可能无法修复。
