# 🤗 Debug 🤗❤️

<img src="https://www.murphysec.com/platform3/v3/badge/1611431819275173888.svg" align="right">

### 如果你使用我的代码时遇到问题，请查看此问题反馈姿势
> 如果这些信息缺失了，我可能不会理睬你

1. 提供完整的错误信息（尽量提供截图）
2. XX仓库的XX分支（最好丢链接给我）
3. 你出错时的编程环境，比如：Python版本号，系统信息（架构，版本等），GCC/G++版本号
4. 你做过哪些尝试？

> 以下是一个完美的示例 ☕
```text
1. xxx文件中第xx行抛出错误：[!] Network Error. （如果是Python报错信息，请直接全部复制给我）
2. git@github.com:xxxxxx/xxxxxxx, v1.0      （HTTP也行，这只是一个示例）
3. GCC版本: 11.2.0，系统：Linux Ubuntu amd64
4. 尝试过断开网络重连，切换网络环境，切换设备等...
```

# About 🍺

<img src="https://github-readme-stats.vercel.app/api?username=sngrotesque&show_icons=true&count_private=true&theme=cobalt&show_icons=true" align="right">

你好~我是SN-Grotesque，欢迎来我的主页。❤<br>
我是一个喜欢代码喜欢绘画喜欢音乐的人，同时也是一个视频博主。<br>
我喜欢研究计算机的深层技术与实现算法，渴望使用最短代码完成最高水准。<br>
> 我可不是一个不善交际的人，但是我已经有一个对象了，他对我非常好。
> 所以请找对象的绕路哦。<br>

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
typedef struct {
    void (*func)(sn_ctx *);
    uint8_t ip_addr[4];
    uint16_t port;
} sn_ctx;

static void CheckIP(sn_ctx *ctx)
{
    printf("%u.%u.%u.%u\n",
        *(ctx->ip_addr + 0), *(ctx->ip_addr + 1),
        *(ctx->ip_addr + 2), *(ctx->ip_addr + 3));
}

static int sn_init_ctx(sn_ctx *ctx, char *ip, uint8_t port)
{
    memcpy(ctx->ip_addr, &inet_addr(ip), sizeof(uint32_t));
    ctx->port = htons(port);
    ctx->func = CheckIP;
}
```



# Skills 🍻

主要使用的语言有"C, C++, Python, Ruby, Perl, Linux Shell, Dos"<br>
我非常喜欢网络安全与计算机密码学，希望可以有同好一起交流。

# Future goals

- 网络安全工程师 - Network Security Engineer
- 画手 - Painter
- 全栈工程师 - Full Stack Developer

# Avocation(Hobby) 🥂

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=sngrotesque&layout=compact" align="right">

1. Cosplay
2. Drink
3. Watch SpongeBob
4. Making love

如果你觉得我的项目不错，那么你可以赞助我🍗/❤/💕，非常感谢！<br>
| [爱发电 - Afdian](https://afdian.net/@sngrotesque) | [PixivFanbox](https://sng.fanbox.cc/) |
| --------------                                    | -----------                           |
> Thank you very much.
