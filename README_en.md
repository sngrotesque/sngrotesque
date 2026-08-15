# Language: English ([中文](README.md))

# About

Hello, I am **Gardenia**, also known as **SN-Grotesque** / **SN**.

I am a developer focusing on C++ and security domains (game security, network security, binary security, web security).  
I used to be a music producer, but now I prefer to invest my time in video creation.  
My primary programming languages are C++ and Python, with auxiliary languages such as Dart / Kotlin / C# / Shell.  
I pursue writing the shortest possible code while achieving the highest quality software engineering.

# 📦 Major Projects

1. [Cheat kernel](https://github.com/sngrotesque/CheatKernel)  
   A **game cheat kernel** I am developing in C++ (currently not open-source).  
   It will mainly target games built on **Unreal Engine** / **Unity** / **Source 2**.  
   The project uses a kernel-mode driver + user-mode process communication to尽可能 bypass anti-cheat detections.  
   Features (a small subset): enumerate and dump process modules, game dumper, DLL injection.

2. [CS2 Die to play](https://github.com/sngrotesque/CS2_Die2Play)  
   A program that automatically browses Douyin (TikTok) after death in CS2 matches, and switches back to the game when respawned.  
   Supports custom URLs / wallpaper changes, etc. Built with Flutter, supports Windows.

3. [HashAll](https://github.com/sngrotesque/HashAll)  
   A file hashing tool to replace `xxx-sum` (`sha256sum` / `md5sum`), implemented in C++ with OpenSSL.

4. [CopyPath](https://github.com/sngrotesque/ContextMenu_CopyPath)  
   A path-copying tool residing in the right-click context menu; more features may be added in the future.

5. [The Wizard's Universal Key (wizard_key)](https://github.com/sngrotesque/wizard_key)  
   This project I worked on for over a year, nearly two years. It was my first serious programming project, written in C++.  
   It once carried my idea of "doing everything," but I eventually realised: **"Focusing on a niche is more important than trying to build a universal tool."**  
   Although it is no longer maintained, it taught me a lot about project management and code quality.

# 🔐 Public Key Verification

To allow users to securely download files I publish, I use **GPG** for signature verification.

- Fingerprint: `003CC84A9F6B10C233114C18F1E31EE85D9E0244`
- Long Key ID: `0xF1E31EE85D9E0244`

You can obtain my public key from [public key servers](https://keys.openpgp.org/) using this information and verify that the files you download were indeed published by me.  
In my repositories, you will find `.asc` / `.sig` files used to verify the integrity and origin of release files.  
If you don't find these verification files, don't panic – they are only used for projects released after July 2026.

If you are not familiar with this, that's fine; it's just a way to confirm that the repository content is indeed written and uploaded by me, and does not affect usage.

# 📞 Contact

- [Bilibili](https://space.bilibili.com/27958784) – My video channel  
- [Gmail](mailto:sngrotesque@gmail.com) – My Google email address

> You may find a YouTube channel by searching `SN-Grotesque`, but that account is no longer active – no need to follow.

# 🤝 Collaboration

I am not currently considering any form of collaboration; I only take commissioned work.

However, if you have an exceptionally good collaborative idea, feel free to pitch it to me (contact above).

# 🛠️ Misc

I have done embedded development (including PCB design and assembly), mainly based on **STM32F103** with **Keil**.

Not much else to say.  
One more thing: **C++ Yes!**