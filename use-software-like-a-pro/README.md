# 善用佳软



> 人和动物最大区别是制造和使用工具。
>
> <p style="text-align: right;">----马克思</p>



很小的时候，我从课本上看到上面这句话，就暗自想，我要是能更多掌握各种工具的使用，就进化得更多一点儿了。虽然这句话现在看来，学术上并不那么正确。后来又学到这句话："工欲善其事，必先利其器"，便更加坚定了我"学习各种工具使用方法"的这个癖好。一直以来，我都在有意识地研究一些计算机"工具"的使用，希望能通过掌握这些技巧，让电脑这个复杂工具更好用，解决自己遇到的实际问题，让自己更"人类"一点儿。



2006年，我开始拥有了属于我自己的电脑，十几年下来，我确实通过不少技巧让电脑更听话，更好用了。身边的朋友发出这样的感叹："同样是电脑，怎么在你手里就那么好使呢"。然而，学习用好工具，并不是非常难的事情，只需要多花一点点时间，就可以掌握。很多人并不在意积累这些技巧，以为在用到的时候，现学也来得及。但是，真到用的时候，急着现去学却往往来不及，也静不下心来学。

经过这么多年的积累，我忽然意识到，它给我带来的真正优势是"时间复利"。在工作和生活中遇到问题时，往往不是只需要某一个技能，而是三五个甚至更多个技能的组合。学习并通过练习掌握一个技能，需要几个小时，而这一堆技能的组合，就需要十几个小时。更何况，如果你从来没有见过这个技能，在遇到问题时，你压根就拆解不出来需要去学习的技能是什么，于是干脆就放弃了。看了别人是如何解决这个问题的，又恍然大悟，进而发出感慨，"哦，原来是这样做的，也不过如此嘛，要是花点时间学习一下这几个技能，我也能做好。"然后，遇到下一个问题时，又重复这个慨叹，继续不会解决。

这些技能没有一个现成的体系，内容东一条西一条很是零散。我看到华为内部流行做"知识书架"的方式来体系化地呈现一个主题的知识，受到启发，于是想用类似的方式整理一下这些知识。这些技巧并不高深，往往都是些最小必要技能，然而我之所至未见许多来者，如果有一本地图，能让同路人更快的跟上我，一起走，走得更远，那，就是这本书的意义了。



[TOC]



## 快速搜索

![visual_expression](images/visual_expression.png?raw=true)

### 只搜索文件名 - everything

2023年，知识工作者已经很少有不知道这个工具的了。



### 快速启动程序 - Listary

这个是window下的一个工具，快速呼起一个文本框，可以直接触达工具和界面。

不过，自动升级成收费版本之后，界面大改，不那么好用了，而且在睡眠的时候经常崩溃中途退出。



### 鼠标快捷键 - Quicker【付费】

https://getquicker.net/

这个工具可以让你的鼠标像键盘一样灵活。对于经常高强度使用Windows的同学，尝试去使用和定制它，你会感谢你自己。

这个软件最厉害的就是鼠标中间呼出菜单。有了菜单，就像呼出了一个工具格子架，每一个格子就是一个马赛克，这个马赛克可以定义，而且像应用商店一样，可以用别人定义好的。

我最喜欢的是截图OCR，随意看到个网址，直接中键呼出，识别出文字，再中键呼出，运行文字，就可以直接打开默认浏览器访问这个网址，连键盘都不需要使用。

<video width="960" height="540" controls>
<source src="https://files.getquicker.net/_sitefiles/media/3-1%E6%88%AA%E5%9B%BEOCR1.mp4" type="video/mp4">
</video>

## 截屏软件



### Snipaste

网址：https://zh.snipaste.com/

不用买专业版，直接下载免费版就已很好用了。



## 查文件夹大小

最早用过的软件是FolderSizes，不过后来收费了。找了一个开源平替，也很方便。

这个软件主要是用在电脑空间不足的情况下，快速定位超大文件，然后删掉或者备份用的。

### WinDirStat

官网：https://windirstat.net/

下载：https://www.fosshub.com/WinDirStat.html



## 查进程和广告弹窗

### ProcessExplorer

广告弹窗是个很烦的东西，要找到真正的讨厌鬼，就要定位这个进程。但是打开任务管理器往往找不到。这个软件可以通过显示的窗口，定位到进程名称，从而，你就可以顺藤摸瓜到那个具体的文件，看看是哪个软件"干的好事"。

这个工具是微软官方家出的，可以放心用：https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer

![image-20231008173802064](README/image-20231008173802064.png?raw=true)

上面箭头指的那个类似靶心![49899240](README/49899240.png)的按钮功能就是通过窗口定位进程的功能。




## 手工文本转录（听写工具）

这是一个在线工具，主要解决听写音频的问题，名字叫做[【oTranscribe】](https://otranscribe.com/)。

代码也是开源的，仓库地址：https://github.com/oTranscribe/oTranscribe



### 场景

这个是记者 [Elliot Bentley](https://twitter.com/elliot_bentley) 写的一个工具。

比如老师的上课录音，拜访客户的会议录音，会议录屏的纪要编写，在线视频的学习等等。

这些音频，直接用mp3转文本的软件处理，一般都很难有比较好的效果，因为它们的口水话特别多，信息密度也比较低。

另外，通过手工打一遍字，一些关键信息也记得牢一点。

更进一步，如果你已经有了AI转换好了的录音，你还可以用它来方便而高效的做**人工校对**。

你是可以用AI工具，但是，当你不想付费或者就想手工过一道的时候，就可以用这个工具。



### 这个软件解决了什么问题？

在语音听写场景下，有几个事挺烦的，这个软件都解决得不错：

* 打字有可能跟不上，需要随时能暂停，不想手离开键盘去摸鼠标，效率太低了
* 倍速播放，但有时还要调整回原来的速度
* 频繁的往前几秒，往后几秒
* 暂停后，播放最好往前倒带一点点，因为有可能因为打字或者思考，想不起来之前那一节是啥，防止漏听



### 隐私安全

这是个网页应用，但是音频文件、文本都保留在浏览器的本地缓存里面，也就意味着，只要能把页面加载进浏览器，你就可以使用它了。

但是请注意，浏览器的缓存容易经常被清除掉，所以，记得及时保存好你的成果。



### 那些快捷键们



#### 音频播放

Esc：播放/暂停
F1（或 Ctrl+1）：倒带
F2（或 Ctrl+2）：快进
F3（或Ctrl+3）：减速
F4（或Ctrl+4）：加速
Ctrl+K：跳转到时间（弹出窗口）
Ctrl+0：返回开始

#### 文字编辑

Ctrl+B：粗体
Ctrl+I：斜体
Ctrl+U：下划线
Ctrl+J：插入时间戳
Ctrl+S：手动备份



## 自动AI转文本工具



### Buzz

https://buzzcaptions.com/

Powered by OpenAI's Whisper

这个是基于Whisper的语音转文字，如果没有显卡，用CPU转文字的速度会比较慢。



### autosub

一个软件叫autosub，是一个命令行的工具，转换字幕依赖于Google speach的api。

仓库地址：https://github.com/agermanidis/autosub



### pyTranscriber

有个哥们基于这个，封装了个gui界面，方便大家用windows来用，这个叫做pyTranscriber。

仓库地址：https://github.com/raryelcostasouza/pyTranscriber



### 讯飞API接口

庄德升写了一个自己用的命令行工具，是基于讯飞的付费API：

仓库地址：https://github.com/mrguangtu/ifly-speach-to-text

## AI绘制图标
### Napkin

Napkin是一个用AI来生成图标的工具。你只要用文字描述你想要的图标,它就能帮你画出来,而且画得挺专业的。

这个工具有几个挺不错的特点:
- 你想要什么样的图标,直接用文字说就行了,不用自己动手画
- 可以选不同的风格和配色,满足各种场景需求
- 生成的图标可以直接用在App、网站或者PPT里面
- 导出的是SVG格式,后期想改还可以继续改
- 用起来特别简单,不管你是设计师还是普通人都能上手

网址：https://www.napkin.ai/

如果你的项目需要大量图标素材,用这个工具就很方便了。你不用一个一个去找图标,也不用花时间自己画,直接描述一下就能生成,省时省力。主要是一个可视化表达，原来构思，现在直接AI生成进行二创。这个效率工具，以后也是要收费的。

## 文本编辑器

文本编辑器是一个宏大的话题，萝卜白菜各有所爱，不同场景主要用的编辑器也不一样，使用最为普遍的是word和wps。Word严格来讲，不应该是一个文本编辑器，更正确的做法是排版器，用好了是可以编辑书稿的。在大学的时候，假期正好有时间，死磕了一本Word排版书半个月，每一个都上手操作，之后常见的排版问题就都学会了，这个技能一直用到今天，受益匪浅，推荐抽空学习一下。

但对于有点逼格的我来说，这些编辑器还不够。我也学习过vim、sublime、notepad++等，不过真正长期稳定用了几年下来的，是下面几个，推荐给大家。

### Markdown神器 - Typora【付费】

[Typora](https://typoraio.cn/)这个工具大名鼎鼎，基本一站式解决了markdown的全部痛点。除了本身简单的所见即所得的编辑模式，也集成第三方image uploader，例如iPic、uPic、Picsee、PicGo、PicList、Upgit等，并支持设置当插入图片时自动上传图床。

最早在1.0以前的版本是免费的，后面成熟之后改成收费的了，还是可以接受的价格，2023年的价格是89CNY激活3台设备永久使用，只要不升级大版本子版本免费更新，买一个非常值得。



### Visual Studio Code

微软开发的[Visual Studio Code](https://code.visualstudio.com/)是一款鼎鼎有名的IDE，而且免费好用。语法高亮、代码自动补全、代码重构等功能该支持的都支持了，是通过加扩展的方式。用这个IDE可以作为文本编辑的补充。

由于支持macros，所以这个编辑器也可以为一些繁琐的操作编程。比如，批量地把书名号`《》`转换为`『』`。



## 图床

仔细研究一下浏览器的原理，你会发现，你看到的每一个图片，都是浏览器一个一个地去对应的URL上下载的。



图床（Image hosting service）是一种在线服务，用于存储、管理和分享图像。就是在网上有个服务帮你存储图片。你把图片丢给图床，图床给你返回一个URL。浏览器就可以通过这个URL来访问你的图片。

![image-20211204143038634](images/NVnW5xaQJRYZg8r.png?raw=true)

图床一般活得比较久，链接相对稳定，内容写完了之后被转载，个人站挂了，但图片在图床里，依然可以访问。另外，图片流量也不小，如果文章火了，流量费也不便宜，传到图床上可以白嫖一些流量，也比较安全，原本要放图片的服务器空间也省了；另外，图床还可以做不少附加功能，比如降分辨率、加水印、CDN加速访问等。



专业的图床服务，大多是收费的。不过，因为能用图床这种技术的人，一般都有点儿技术基础，所以也搞出了不少免费的方案，比如github仓库当图床之类的路子。



### 图床网站

架设一个图床真心没啥技术门槛，所以这样的图床网站往往多如牛毛，甚至你去网上搜一篇教程来，也能架设一个。如果不是必须自己host，直接用现成的服务比较省事。下面是2021年能用的一些图床的名称，可以自行搜索用法哈：



- SMMS: https://sm.ms/

- 七牛图床

- 腾讯云COS

- 又拍云

- GitHub图床

- 阿里云OSS

- Imgur图床



### 图床上传工具

**图床上传工具是帮助你把图片上传到图床的工具。**你传一个文件到服务器上，还是挺麻烦的。打开网页，选择图片，上传，得到url，粘贴到markdown中。这个过程越繁琐，就越影响写作的思路。所以，你需要一个图床工具来帮助你，无感而自动地上传到图床上是最好的了。这类工具有的常驻任务栏，有的集成到工具里。你只要把图片通过快捷键、剪贴板之类的快捷键操作指定，它就会自动帮你完成上传，获取URL，并反向写入你的剪切板，你直接粘贴到你想要的地方就行了。甚至，你可以直接在typora里面，配置这样的工具，自动将本地图片批量上传到图床服务器上。



下面几个工具，都是windows版的哈。



#### PicGo

typora文档直接提供了这个软件的介绍，可以参考这里：https://support.typora.io/Upload-Image/#picgo-core-command-line-opensource



这是PicGo的官网文档：https://picgo.github.io/PicGo-Doc/



![](images/New_LOGO-150.png?raw=true)



![](images/picgo-2.0.gif?raw=true)



[picgo的图床配置方法戳这里...](https://picgo.github.io/PicGo-Doc/zh/guide/config.html#%E5%9B%BE%E5%BA%8A%E5%8C%BA)





#### MPic

开发软件这哥们原来叫做 |忒斯拉不会飞|，哈哈哈好有意思的名字。好像很久都没更新了，以前的仓库地址，已经废弃了：https://github.com/TeslaFly01/MPic

2023年发现作者迁移到gitee了：https://gitee.com/izhaofu

仓库在这，不过没有发release了：https://gitee.com/ChartBed/MPic



[工具的用法戳这里...](https://elmagnifico.tech/2018/08/14/MPic/)



## rss阅读器 - Irreader【付费】

给自己构建一个深度阅读的环境，自动在指定信息源获得信息，然后进入下一步，变成Action。

这是一个信息源的收集器，你在这里**本地化地**管理你的信息源，而不是在线。这样不管怎么切换，你的信息源就是你的信息源。

当然，充会员可以无限订阅源。



## 非主流聊天室 - Discord

很多年轻一代的APP都用这个做BBS，其实也未尝不可，无非是一种新的信息组成形式。



## 漫画头像 - FaceYourManga

https://faceyourmanga.com/

这个是个很好玩的做卡通头像的网站。它把每一个构成头像的元素都拆得非常细，因此可以自己画出自己喜欢的漫画头像。我的漫画头像也是用这个网站做出来的，大约是在2006年做的，一直沿用到今天。今天一看，这个古老的网站还在。

![](images/faceyourmanga.jpg?raw=true)

一个有趣的玩法是，你自己定义了一个卡通形象肉身，在同一个卡通人的肉身上，给它换帽子，换衣服，染头发等等，实现虚拟形象的换装，配合不同场景更换头像玩。



## 包管理器

包管理器，可能你以前没有听说过这个词，你可以把它想象成"应用商店"，Chrome浏览器有应用商店、苹果、华为、小米等手机都有自己的应用商店。你在应用商店里面可以选择程序下载，升级，卸载对应的程序。包管理器，也是干这事儿的。

如果你要为一个新设备准备好环境，你可以写一个脚本，让包管理器自动的按照清单下载和安装好，这就会比较方便。



### Windows原装的 - winget

关于这个工具，微软的WinGet PM Demitrius Nelon 做了一个视频来介绍这个工具，可以参考[这里](https://learn.microsoft.com/zh-cn/shows/open-at-microsoft/intro-to-windows-package-manager)。





## 静态站工具

### 简单的文档站生成器 - docsify

用markdown来host静态站点，[docsify](https://docsify.js.org/#/)极其简单，功能都写到js里面，一个index.html就可以搞定，只需要准备很少的东西就可以了，几乎不用怎么改页面。适合在线文档、书籍等静态的、一经发布几乎不会大变动的内容，也不需要交互。

- markdown内容
- github pages



### 快速、简介且高效的博客框架 - Hexo

[Hexo](https://hexo.io/)也是一个静态站工具，不过是要用写好的模板，通过markdown生成一道。

好处是可以做出灵活多变的站点，而且不用暴露md文件本身。还可以集成各种第三方工具。



## 正则表达式

正则表达式非常灵活，如果不学会，很多文字处理的高级功能都没法做成自动化的，对于字符串处理、文字处理编程等方面，是个绕不开的基本知识。然而，正则是一个"学完就用，常学常新，用完就忘"的一个技能。

现在有ChatGPT了，可以帮助生成正则表达式，但是如果不够精准，还是需要手动调试的。

### 在线调正则的工具 - Regex101

https://regex101.com/

正则表达式麻烦的是，如果不能在网上直接搜到特定的表达式，就要想办法自己描述。但是如果稍微复杂一点，就容易搞不清楚。所以如果有一个工具来辅助调试，就会事半功倍。

Regex101就是个在线调正则的工具，SaaS形式，随开随用非常方便。



## 视频下载

有需要要把视频下载下来，尤其是B站的。有的时候，做个备份，因为视频会被河蟹。有的时候，作为素材，放在自己盘里，随时可以找到查看，或者二次创作。

这种一般有两种思路，一种是浏览器插件，一种是专用的视频下载软件。



### 流媒体下载 - CocoCut

这是Chrome的一个插件，在应用商店里面可以找到。CocoCut是最佳m3u8下载器Chrome扩展程序，可快速轻松地下载Chrome中的m3u8或音频。可以自动嗅探视频并提供下载链接，如果遇到有加密的视频可以开启录制模式。

https://cococut.net/

Tips：如果需要加速下载，在开发者模式里面，找到视频的标签，用JS把playbackRate改成16就最快了。



### B站视频下载器【单机软件】

https://github.com/BilibiliVideoDownload/BilibiliVideoDownload



## AI Galary

### KALOS Art Libery 

一个MidJourney的抄 prompt 的地方。

https://lib.kalos.art/



### Midjourney

这个大家都知道，人工智能画图的。只不过如果不会科学上网，2023年是无法使用的。

不太喜欢的是MidJourney要强制使用discord，这个用户体验并不是很好，略微吐槽一下。



## 探索ing

### 好玩的Web3博客 - xlog

https://xlog.app/about

知道这个是因为看到xlog的作者给宠物猫的AirTag上打印了个[域名](https://suannai.cat/)，记录猫咪的各种，真是宠猫宠到了天上。

![图像](https://pbs.twimg.com/media/F6E2SYEaEAAb9rB?format=jpg&name=4096x4096)

后来才知道，xlog就是rss3大佬DIYgod搞的新项目。

关于这个产品，可以听听作者自己的首次[播客](https://podcasts.apple.com/cn/podcast/no-28-%E5%92%8Cxlog-app%E7%9A%84%E4%BD%9C%E8%80%85diygod%E8%81%8A%E5%8C%BA%E5%9D%97%E9%93%BE%E5%92%8C%E5%8D%9A%E5%AE%A2%E5%B9%B3%E5%8F%B0-%E5%89%8D%E7%AB%AF%E5%AD%A6%E4%B9%A0%E5%92%8C%E7%94%9F%E6%B4%BB%E6%84%9F%E6%82%9F/id1586927144?i=1000619271886)。你可以自己host，但是，数据在链上。当然，访问链上数据很慢，所以有一个数据库，平时都是从数据库里面取。另外，有个媚点功能，ChatGPT自动总结内容，节约时间。

