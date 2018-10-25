#  Vim同时进行多行注释

标签(空格分隔)： CentOS Vi/Vim 多行注释

---
在使用**vi/vim**编辑器对代码或者配置文件编辑的时候，我们经常会需要对多行添加注释或者删除多行的注释。 我们为记录思想和分享知识提供更专业的工具。 您可以使用 Cmd Markdown：

#### 工具
> * Vi/Vim编辑器

## 操作
1.进入/vim编辑器，按CTRL+V进入可视化模式（VISUAL BLOCK）

![Ctrl+V可视界面](https://raw.githubusercontent.com/smartZdw/image-/master/img/1.png)

2.移动光标上移或者下移，选中多行的开头，如下图所示
![上下选中行](https://raw.githubusercontent.com/smartZdw/image-/master/img/2.png)

3.选择完毕后，按大写的的I键，此时下方会提示进入“insert”模式，输入你要插入的注释符，例如#
![](https://raw.githubusercontent.com/smartZdw/image-/master/img/3.png)

4.最后按ESC键，你就会发现多行代码已经被注释了(即下面所有行首都加上了一个"#")
![](https://raw.githubusercontent.com/smartZdw/image-/master/img/4.png)

5.删除多行注释的方法，同样 Ctrl+v 进入列选择模式，移到光标把注释符选中，按下d，注释就被删除了。




>* 大肚能容!      容世间可容之事

>* 开口便笑!      笑世间可笑之人

>* ---------------------------------------------------------------------------smartZhou
