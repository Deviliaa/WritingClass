> 转载自王晋东的知乎文章：https://www.zhihu.com/people/jindongwang



##  ResearchGo:研究生活第七帖——写论文、做PPT、写文档必备工具

本次整理了我在读博过程中，写论文、做PPT、写文档经常用的各种工具，每种都是我精挑细选试错以后留存的结果。特此分享给大家，希望大家在做这些事的时候，不要被工具扰乱思绪，全心全意扑在研究上，达到事半功倍的效果。

工具千万条，好用第一条。我们这里大多数工具均以用LaTex为例(用word的小伙伴可以选择性忽略)。我们将介绍以下工具软件：

- 用于日常写LaTex的TexStudio
- 用于制作LaTex表格的网站Tablesgenerator
- 用于复制别人公式的Mathpix
- 用于快速写LaTex数学公式的在线公式编辑器
- 用于多人协作的Overleaf
- 用于word和ppt的公式神器AxMath
- 用于写markdown的Visual Studio Code
- 用于画图的PPT(没错，就是PPT)
- 用于论文查错的网站Grammarly
- 用于PPT和论文画图的islide插件

先强调一下，萝卜青菜，各有所爱。我用的这些工具不代表是最好的，是我认为最满足我科研需求的。我并不是打广告哦。

### 用于日常写LaTex的TexStudio

TexStudio是一个开源LaTex编辑器，拥有最完整的编辑体验。最重要的是，安装完Tex内核以后，直接安装TexStudio即可使用，完全不用配置！我特别神烦那些需要各种配置的东西(对，说的就是用sublime和vscode的)，既浪费时间，又没意义。

TexStudio是开源的跨平台软件，支持Windows、MacOS、Linux。有一个叫TexMate的软件与其很像，但是我体验过，没有TexStudio好用。TexStudio有个缺点就是没有内置好主题色彩，因此刚安装好是惨白色，对眼睛极不友好。我们可以在高级设置里自己更改配色。希望官方对内置主题的支持早日到来。

Tips：TexStudio在编译时，如果你已打开了该PDF则编译失败。那又不想每次都关了。这时候你需要神器sumatrapdf作为外部预览工具!

TexStudio下载地址：[http://www.texstudio.org/](https://link.zhihu.com/?target=http%3A//www.texstudio.org/)

### 用于制作LaTex表格的网站Tablesgenerator

既然写论文，免不了要制作表格。LaTex表格语法又很冗长，非常不利于我们编写表格。我们的表格结果经常是放在Excel里的，有没有办法将Excel表格导出成LaTex？之前有一些插件，但都不好用。直到Tablesgenerator网站的出现。

你可以直接复制Excel中的内容粘贴到网站上，所有事情都解决了。网站还提供了一些简单的编辑功能。以我的研究经验来看，足够了。毕竟你不是要做一个超级复杂的表格。除此之外，该网站还支持导出Markdown、html等格式的表格，非常良心！

![img](https://pic3.zhimg.com/80/v2-d883f25ce5b140c26ee50a5faa6ca89d_720w.jpg)

Tablesgenerator

Tablesgenerator网站地址：[https://www.tablesgenerator.com](https://link.zhihu.com/?target=https%3A//www.tablesgenerator.com/)

### 用于复制别人公式的Mathpix

很多时候我们需要借鉴(抄)别人已有的公式放到自己文章中，以进行二次修改。简单的还好，要是很复杂的话，写起来简直崩溃。这时候我们就需要一个能进行公式OCR的软件：截图或拍照，公式马上变成LaTex代码。

Mathpix就是完成这个任务的神器。你只需要下载安装，然后选中区域进行截图，该软件马上就会为你生成对应的LaTex代码。个人体验这么久，从来，是从来，没出错过！它是跨平台的，还有手机客户端，可以拍照识别。官网上还卖萌地放上了牛顿和爱因斯坦的评语，哈哈！

![img](https://pic3.zhimg.com/80/v2-24cb94987bac421f51ce69d787b6aaec_720w.jpg)

Mathpix

Mathpix下载地址：[https://mathpix.com/](https://mathpix.com/)

### 用于快速写LaTex数学公式的在线公式编辑器

很多时候我们只是想写个LaTex公式，不想新建工程-文件-编译。我就是想写个公式，放到word、ppt里。或者，我就是想验证一下我的代码对不对。这时候，你需要codecogs提供的在线LaTex公式网站。

该网站可以实时将LaTex代码转换为可见的公式，方便下载导出。

![img](https://picb.zhimg.com/80/v2-378b527210febfec3af9018ffe85409b_720w.jpg)

在线公式编辑器网址：[https://www.codecogs.com/latex/eqneditor.php?lang=zh-cn](https://www.codecogs.com/latex/eqneditor.php%3Flang%3Dzh-cn)

### 用于多人协作的Overleaf

多个人写LaTex、改论文，如何同步？Overleaf是神器。不说了。

Overleaf网址：[https://www.overleaf.com/](https://www.overleaf.com/)

### 用于word和ppt的公式神器AxMath

如果我们在word和ppt中有书写公式的要求，可以使用AxMath。它支持所见即所得，也支持写LaTex代码转换为公式。在淘宝有卖，作者是一位浙江工业大学的老师，只要几十块就行，比笨重难看的Mathtype好用不要太多！

![img](https://pic4.zhimg.com/80/v2-5bc0562c2612654c5a9acecdd9219495_720w.jpg)

Axmath

AxMath地址：[http://www.amyxun.com/](https://www.amyxun.com/)

### 用于写markdown的Visual Studio Code

如果你是临时写文档、简短报告，那么Markdown将是你的不二选择。Markdown编辑器非常多，我体验过很多以后，只推荐Visual Studio Code。实时预览、自动补全、界面友好大气！它还是跨平台开源免费的，支持众多常用编程语言，是Github上最火热的项目之一！

Visual Studio Code下载地址：[https://code.visualstudio.com/](https://code.visualstudio.com/)

### 用于画图的PPT

你没看错。如果你有画图需求(比如，展示自己的idea、画流程图)，那么PPT将是你的不二选择！它支持导出高清矢量PDF，而且PPT本身就可以支持你画众多的图。你可以画深度网络，可以画概率分布，还可以画方法流程图。只有你想不到，没有PPT画不出来！当然，要画严谨的折线、柱状、分布图什么的，还是需要Excel、Matlab、Python等专业工具/语言的。

![img](https://picb.zhimg.com/80/v2-8650487631b7ba248b696a32c3f06797_720w.jpg)

用PPT画的神经网络图

PPT下载地址就不说了。

### 用于论文查错的网站Grammarly

论文写好了，总得查查语法错误吧？又不想一个人读下来，又不相信自己的英语水平。怎么办？这时候，你需要Grammarly网站帮你自动查错！就算是Latex源域复制进去也可以！网站是免费使用的，高级功能需要付费。不过我觉得，免费功能就足够了。

Grammarly网址：[www.grammarly.com](https://www.grammarly.com/)

## 用于PPT、论文画图的islide插件

我们经常需要在PPT或者论文中画一些示意图，比如画一个人像、一个手机、一个建筑等。通常情况下我们会通过一些搜索引擎来搜索想要的图片。然而此过程繁琐且质量不可保证，尤其无法得到放大不失真的矢量图。推荐一个PPT插件，名字叫做islide，它里面不仅包括了辅助做PPT的很多工具，同时还内置了几万种各类的矢量图标和图片。我个人的论文和PPT就多次用到了此工具。全功能需要付费，不过也不是很贵，可以接受。

Islide下载地址：[https://www.islide.cc/](https://www.islide.cc/)
