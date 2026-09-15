语言：（中文 / [English](README_en.md)）

# 关于

你好，我是 **栀子鱼鱼花**，也可以叫我 **SN-Grotesque** / **SN**。  

我是一名开发者，主要聚焦于 C++ 和安全层面（游戏安全，网络安全，二进制安全，Web安全）。  
曾经是一位音乐制作者和游戏开发者，现如今更愿意投入视频制作行列。  
编程语言层面主要使用 C++ 和 Python 两门语言，其他辅助语言有如 Dart / Kotlin / C# / Shell 等。  
追求使用最短代码实现最高质量的软件工程。

# 📦 主要项目

1. [Cheat kernel](https://github.com/sngrotesque/CheatKernel)  
    这是我正在使用 C++ 编写的一款 **游戏作弊内核**，目前暂 **不考虑开源**。  
    将主要聚焦于 **Unreal engine** / **Unity** / **Source 2** 开发的游戏。  
    此项目使用内核态驱动 + 用户态进程的方式通信，以尽可能的绕过游戏反作弊的检测。

2. [OP4](https://github.com/sngrotesque/OP4-Cipher)  
    这是我自己开发的块密码算法，追求使用最简单的方式实现高安全性的加密。  
    添加了 **SIMD** 支持，**AVX2** 测试性能超过 OpenSSL 中的 **ChaCha20**。
    实际场景下请使用 `AES` / `ChaCha20` 等经过充分测试的加密算法。

3. [KanamiChat](https://github.com/sngrotesque/KanamiChat)  
    使用 Flutter 框架编写的多平台 AI 聊天软件，未来会支持更多的角色。  
    此项目当前不属于我的主要开发项目，请期待未来的更新。  

    目前支持的角色如下：
    - 香奈美（卡拉彼丘）
    - 星绘（卡拉彼丘）

4. [CS2 Die to play](https://github.com/sngrotesque/CS2_Die2Play)  
    一款 CS2 对局中死亡后自动刷抖音的程序，复活时切回游戏。  
    支持 自定义网址 / 更换壁纸 等，使用 Flutter 框架编写，支持 Windows 平台。

5. [HashAll](https://github.com/sngrotesque/HashAll)  
    一款用于替代 `xxx-sum` (`sha256sum` / `md5sum`) 的文件哈希工具，使用 C++ 结合 OpenSSL 库实现。

6. [CopyPath](https://github.com/sngrotesque/ContextMenu_CopyPath)  
    一款常驻于右键菜单的路径复制工具，未来可能会添加更多功能。

7. [The Wizard's Universal Key (wizard_key)](https://github.com/sngrotesque/wizard_key)  
    这个项目我写了一年多，将近两年，它是我第一个尝试的正式编程项目，使用 C++ 编写。  
    它曾经承载了我“想做所有事情”的想法，但最终我意识到：“**聚焦细分领域比试图做一个万能工具更重要**”。  
    虽然目前已停止维护，但它让我在项目管理与代码质量方面成长了很多。

# 🔐 公钥验证

为了让用户能够放心下载我发布的文件，我使用了 **GPG** 来进行签名验证。

- 公钥指纹 (Fingerprint)  `003CC84A9F6B10C233114C18F1E31EE85D9E0244`
- 长密钥 ID (Key ID)  `0xF1E31EE85D9E0244`

你可以通过这些信息在[公钥服务器](https://keys.openpgp.org/)中获取我的公钥，并验证你下载的文件是否确实由我本人发布。  
在我的仓库中你会看到 `.asc` / `.sig` 文件，它们用于验证发布文件的完整性与来源。  
如果你没有找到这些验证用途的文件也不要惊慌，因为它只会用在 2026 年 7 月之后的项目。

如果你不了解这是什么也没关系，这个只是用于确认仓库项目是否确实是我本人编写和上传的而已，不会影响对项目的使用。

# 📞 联系方式

- [哔哩哔哩 / Bilibili](https://space.bilibili.com/27958784) - 我的视频账号
- [谷歌邮箱 / Gmail](mailto:sngrotesque@gmail.com) - 我的谷歌邮箱地址

> 你可能会在 Youtube 通过搜索 `SN-Grotesque` 找到一个 YouTube 账号，但那个账号我已经未在经营了，无需关注。

# 🤝 合作

目前不考虑任何形式的合作，只接单。

或者你如果有实在觉得好的合作方面的想法，可以提给我试试看（联系方式在上面）。
