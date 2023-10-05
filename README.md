# VS_Generate-event_RCE
这是我在HTB的visual机器中遇到的visual-studio编译生成成功时的命令执行

在编译生成.net项目的时候可以通过右击“项目”选择“属性”，然后在“事件”中输入生成可执行程序成功前/后要执行的命令

![image-20231005112328401](https://raw.githubusercontent.com/yxl2001/Note-drawing-bed/main/images/202310051123435.png)

之后点击“生成”-->"生成解决方案"，会执行calc.exe弹出计算器。



对于后续要修改执行的命令可以在项目的.csproj中快速修改

![image-20231005112541403](https://raw.githubusercontent.com/yxl2001/Note-drawing-bed/main/images/202310051125294.png)
