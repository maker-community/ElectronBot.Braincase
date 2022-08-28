# ElectronBot.Braincase
电子脑壳上位机程序的一些说明，目前应用只开源的SDK部分。

![应用首页](/Images/home.png)

# 关于技术栈
采用[（windows App SDK）WASDK](https://docs.microsoft.com/zh-cn/windows/apps/windows-app-sdk/)应用开发框架，这个可以根据链接进行查看，主要讲解SDK Demo如何使用。

## 开发环境安装
### 1. 安装Visual Studio 2022
首先去官方下载[社区版](https://visualstudio.microsoft.com/zh-hans/vs/)安装包，然后选择要安装的组件，如下图。
![install](/Images/install.png)
### 2. 安装WASDK开发组件
[Windows 应用 SDK](https://docs.microsoft.com/zh-cn/windows/apps/windows-app-sdk/)相关介绍文档。

如下图，下载组件进行安装。[链接地址](https://docs.microsoft.com/zh-cn/windows/apps/windows-app-sdk/downloads)
![tool](/Images/download-tool.png)
安装完成启动Visual Studio 2022选择WinUI创建项目测试项目，如果能够正常运行就可以运行SDK Demo了。

[SDK仓库传送门](https://github.com/maker-community/ElectronBot.DotNet)

# 关于参考的一些项目

+ [项目模板——TemplateStudio](https://github.com/microsoft/TemplateStudio)

+ [表盘参考项目——一个番茄钟](https://github.com/DinoChan/OnePomodoro)
+ [社区工具集——CommunityToolkit](https://github.com/CommunityToolkit/WindowsCommunityToolkit)

+ [控件库展示demo——WinUI-Gallery](https://github.com/microsoft/WinUI-Gallery)

+ [图像处理库——opencvsharp](https://github.com/shimat/opencvsharp)

+ [Emoji8 表情识别例子](https://github.com/microsoft/Windows-Machine-Learning/tree/master/Samples/Emoji8/UWP/cs)

# 关于功能介绍

+ 表情和动作 

目前加入了表情的播放，并且是可以通过电脑的声音设备播放，表情加动作会在后期进行加入。

+ 表情识别

表情识别是参考了[Emoji8](https://github.com/microsoft/Windows-Machine-Learning/tree/master/Samples/Emoji8/UWP/cs)这个项目进行制作的，通过表情识别截图脸部数据，然后通过usb将数据传输到电子的屏幕上，制作成了量子纠缠。

![表情页](/Images/emoji.png)

# 关于后期的功能

+ 优化表情和动作
+ 手势触发语音识别进行控制
+ 进行定时播报
+ 多电子连接

待定。。。。
