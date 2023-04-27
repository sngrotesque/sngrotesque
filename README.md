# 😋 贡献

<img src="https://www.murphysec.com/platform3/v3/badge/1611431819275173888.svg" align="right">
<a href="https://stackexchange.com/users/23032190"><img src="https://stackexchange.com/users/flair/23032190.png" width="208" height="58" alt="profile for S-N on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for S-N on Stack Exchange, a network of free, community-driven Q&amp;A sites"></a>

# 🤗 Debug 🤗❤️

### 如果你使用我的代码时遇到问题，请参考StackOverflow的提问姿势。

如果你提的问题特别的让人无语或者是太过于基础，那么我心中对你的印象分会降低非常多。

> 具体可以参考[Angelina-Bot](https://www.angelina-bot.top/About.html)的智力对照表

| 智力得分	| 提问方式 |
| :--- | :--- |
| 100分	| 我在xxx遇到了一个问题，在翻阅文档和视频后，这里是报错截图，我参考了百度或谷歌中xxx文章进行解决，但仍不能解决 |
| 90分	| 我遇到了xxx问题，我翻阅了文档和视频，没有找到解决方案，完整的报错截图如下 |
| 60分	| 这里是完整的报错截图，请问应该怎么解决 |
| 10分	| 这咋回事啊（手机拍屏幕）|
| 0分	| 这怎么办啊（不完整的报错截图） |
| sb	| 大神求带、这怎么不能用了、我打不开了、你们这个正常吗、文件在哪啊、怎么学啊、我是小白能帮我吗 |

# About 🍺

你好~我是SN-Grotesque，欢迎来我的主页。❤<br>
我是一个喜欢代码喜欢绘画喜欢音乐的人，同时也是一个视频博主。<br>
我喜欢研究计算机的深层技术与实现算法，渴望使用最短代码完成最高水准。<br>
<!-- > 我可不是一个不善交际的人，但是我已经有一个对象了，他对我非常好。
> 所以请找对象的绕路哦。<br> -->

以下为我的个人主页相关网站传送门

<!--
| 平台名称         | 网站超链接                                     |
|------------------|------------------------------------------------|
| Pixiv            | <a href="https://www.pixiv.net/users/38279179"><img src="https://www.pixiv.net/favicon.ico" width="15px" height="15px"></a> |
| Youtube          | <a href="https://www.youtube.com/channel/UCITRiFd37VZS8y4vjW2pfYQ/featured"><img src="https://www.youtube.com/favicon.ico" width="15px" height="15px"></a> |
| 哔哩哔哩         | <a href="https://space.bilibili.com/27958784"><img src="https://www.bilibili.com/favicon.ico" width="15px" height="15px"></a> |
| Soundcloud       | <a href="https://soundcloud.com/sngrotesque"><img src="https://soundcloud.com/favicon.ico" width="15px" height="15px"></a> |
| PixivFanbox      | <a href="https://sng.fanbox.cc/"><img src="https://sng.fanbox.cc/favicon.ico" width="15px" height="15px"></a> |
| Twitter          | <a href="https://twitter.com/SNGOfficial4"><img src="https://twitter.com/favicon.ico" width="15px" height="15px"></a> |
| 网易云音乐       | <a href="https://music.163.com/#/user/home?id=1686139386"><img src="http://s1.music.126.net/style/favicon.ico" width="15px" height="15px"></a> |
| 知乎             | <a href="https://www.zhihu.com/people/kianakaslana-16"><img src="https://www.zhihu.com/favicon.ico" width="15px" height="15px"></a> |
| 爱发电           | <a href="https://afdian.net/@sngrotesque"><img src="https://afdian.net/favicon.ico" width="15px" height="15px"></a> |
-->

<table>
    <tr>
        <td>Pixiv</td>      <td>Youtube</td>     <td>哔哩哔哩</td>    <td>Soundcloud</td>    <td>PixivFanbox</td>
        <td>Twitter</td>    <td>网易云音乐</td>  <td>知乎</td>        <td>爱发电</td>
    </tr>
    <tr>
        <td><a href="https://www.pixiv.net/users/38279179"><img src="https://www.pixiv.net/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://www.youtube.com/channel/UCITRiFd37VZS8y4vjW2pfYQ/featured">
            <img src="https://www.youtube.com/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://space.bilibili.com/27958784"><img src="https://www.bilibili.com/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://soundcloud.com/sngrotesque"><img src="https://soundcloud.com/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://sng.fanbox.cc/"><img src="https://sng.fanbox.cc/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://twitter.com/SNGOfficial4"><img src="https://twitter.com/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://music.163.com/#/user/home?id=1686139386">
            <img src="http://s1.music.126.net/style/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://www.zhihu.com/people/kianakaslana-16"><img src="https://www.zhihu.com/favicon.ico" width="15px" height="15px"></a></td>
        <td><a href="https://afdian.net/@sngrotesque"><img src="https://afdian.net/favicon.ico" width="15px" height="15px"></a></td>
    </tr>
</table>

```c
typedef struct snObject {
    snByte *buf;
    snSize size;
    snSize addr_start;
    snSize addr_stop;
    snVoid (*func)(snByte *, snSize);
    snObject *next;
} snObject;

SN_STATIC_FUNC(snError) snObject_malloc_init(snObject *ctx,
    snSize _Request_memory_size, snBool _Clear_memory_space_data)
{
    ctx->buf = (snByte *)malloc(_Request_memory_size);
    if(!ctx->buf)
        return _Err_Memory;
    if(_Clear_memory_space_data)
        memset(ctx->buf, 0, _Request_memory_size);
    ctx->size = _Request_memory_size;
    ctx->addr_start = (snSize)&ctx->buf;
    ctx->addr_stop = ctx->addr_start + ctx->size;
    return _Err_Normal;
}
```

# Skills 🍻

主要使用的语言有`C`, `C++`, `Python`，偶尔使用或正在学习的语言有`Java`, `C#`, `Ruby`, `Rust`, `Perl`。<br>
我非常喜欢网络安全与计算机密码学，希望可以有同好一起交流。

# Future goals
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=sngrotesque&layout=compact" align="right">

- 网络安全工程师 - Network Security Engineer
- 画手 - Painter
- 全栈工程师 - Full Stack Developer

# Avocation(Hobby) 🥂
<img src="https://github-readme-stats.vercel.app/api?username=sngrotesque&show_icons=true&count_private=true&theme=cobalt&show_icons=true" align="right">

1. Cosplay
2. Drink
3. Watch SpongeBob
4. Making love

如果你觉得我的项目不错，那么你可以赞助我🍗/❤/💕，非常感谢！<br>
| [爱发电 - Afdian](https://afdian.net/@sngrotesque) | [PixivFanbox](https://sng.fanbox.cc/) |
| --------------                                    | -----------                           |
> Thank you very much.
