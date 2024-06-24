# About

你好，我是**SN-Grotesque**，欢迎你的到来。  
我是一个[开发者](https://github.com/sngrotesque)，也是一个[音乐人](https://music.163.com/#/artist?id=30774062)，同时也是一个[视频制作者](https://space.bilibili.com/27958784)。  
当然也是一个游戏制作者，使用[Unity 2021](https://unity.com/cn/products)与[Unreal Engine 5](https://www.unrealengine.com/en-US/unreal-engine-5)进行游戏的开发，使用[WWise](https://www.audiokinetic.com/zh/wwise/overview/)进行游戏音效的设计和制作，使用[FL Studio](https://www.image-line.com/)进行游戏音乐的制作，使用[Visual Studio 2022 LTSC 17.6](https://learn.microsoft.com/zh-cn/visualstudio/releases/2022/release-notes-v17.6)作为代码编辑器（作为一个长期支持版本，以及能够兼容UE5的版本）。  
常规开发时，我喜欢使用[Visual Studio Code (VSCode)](https://code.visualstudio.com/)与[MSYS2](https://www.msys2.org/)进行代码的编写。  
我喜欢研究很多东西，包括计算机底层的各种技术和算法实现，渴望使用最短代码做到最高水准。  

# Projects
 - [WMKC](https://github.com/sngrotesque/WMKC/)，这是我主力开发的[C++](https://en.wikipedia.org/wiki/C%2B%2B)库，用于未来我的[即时通讯软件](https://en.wikipedia.org/wiki/Instant_messaging)的底层，可以理解为一个为了支持未来软件而开发的框架。试图做到[Telegram](https://telegram.org/)那样的程度。
 - [WMKC for Python](https://github.com/sngrotesque/WMKC_Python/)，这是我使用[Python3](https://www.python.org/)进行开发的一些库，其中包含了[Pixiv爬虫](https://github.com/sngrotesque/WMKC_Python/blob/v1.0.0/wtools/pixiv.py)，[哔哩哔哩爬虫](https://github.com/sngrotesque/WMKC_Python/tree/v1.0.0/Web%20crawler/bilibili)以及[E-Hentai爬虫](https://github.com/sngrotesque/WMKC_Python/tree/v1.0.0/Web%20crawler/ehentai)。  
 其实主要开发用于未来项目的一些框架，但与[WMKC](https://github.com/sngrotesque/WMKC/)不同的是，此仓库的代码偏向于更高层的功能。而前者则是更底层的实现。

# Contact

<a href="https://stackoverflow.com/users/21376217/s-n"><img src="https://stackoverflow.com/users/flair/21376217.png?theme=hotdog" width="208" height="58" alt="profile for S-N at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for S-N at Stack Overflow, Q&amp;A for professional and enthusiast programmers" align="right"></a>

 - [哔哩哔哩](https://space.bilibili.com/27958784)，这是我在Bilibili平台的创作账号，欢迎关注。
 - [Telegram](https://t.me/SNSTUPID)，这是我唯一一个国外即时通讯软件的联系方式（曾经有用过[LINE](https://line.me/en/)，但后来放弃了）。
 - [Gmail](mailto:sngrotesque@gmail.com)，通过谷歌邮箱联系我，请注意你的邮件标题，否则我可能会在未查看的情况下直接删除你发送的邮件。
 - [W](https://x.com/CNSN_W)，这是我多个Twitter账号的其中一个。

# Collaboration (?)

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=sngrotesque&title_color=ffff00&bg_color=151515&text_color=efefef&hide_border=true&layout=compact" align="right">

如果你要与我合作开发代码，下面是我的代码风格，你可以参考一下自己是否能够接受。  
我的代码风格还是很规范化的，注释方式，采用业界通用的[Doxygen注释](https://www.doxygen.nl/manual/docblocks.html)。  
我使用的语言为：[`C`, `Python`, `C++`, `C#`, `Java`]，目前不会使用Java作为开发语言[^WhyNotUseJAVA]。

```cpp
namespace wmkc {
    class IM {
    private:
        Socket fd;
        size_t session_id;
    public:
        IM(Socket fd, size_t session_id)
        : session_id(session_id)
        {
            //...
        }

        /**
         * @brief 发送用户消息
         * @param message 用户消息
         * @param seq 此消息的序号，用于纠正包的顺序
         * @return 无
         */
        void send_msg(std::string message, uint32_t seq)
        {
            // All kinds of other things...
            fd.send(message);
            // All kinds of other things...
        }
};
}
```

---

[^WhyNotUseJAVA]: 原因是Java那又臭又长的语法以及又臭又长的目录结构，真的很恶心我，并且它的[性能](https://goodmanwen.github.io/Programming-Language-Benchmarks-Visualization/)相比较于C/C++/C#并没有优势。
