Language: (中文 / [English](README_en.md))

# About

Hi, I'm **SN-Grotesque**, also known as **SN**.  

I'm a developer focused primarily on C++ and security-related fields (game security, network security, binary security, and web security).  
I used to be a music producer and game developer, but nowadays I prefer investing my time in video creation.  
My main programming languages are C++ and Python, with auxiliary languages including Dart, Kotlin, C#, Shell, and others.  
I strive to achieve the highest-quality software engineering with the shortest possible code.

# 📦 Main Projects

1. [Cheat kernel](https://github.com/sngrotesque/CheatKernel)  
   A **game cheat kernel** I'm writing in C++. Currently, **open-sourcing is not planned**.  
   It primarily targets games developed with **Unreal Engine** / **Unity** / **Source 2**.  
   This project uses kernel-mode drivers combined with a user-mode process for communication, in order to bypass game anti-cheat detection as much as possible.

2. [OP4](https://github.com/sngrotesque/OP4-Cipher)  
   A block cipher algorithm I developed myself, pursuing high-security encryption with the simplest possible implementation.  
   **SIMD** support is included — **AVX2** performance exceeds **ChaCha20** in OpenSSL during testing.  
   For real-world usage, please use thoroughly tested algorithms like `AES` / `ChaCha20` instead.

3. [KanamiChat](https://github.com/sngrotesque/KanamiChat)  
   A cross-platform AI chat application written with the Flutter framework. More characters will be supported in the future.  
   This project is currently not one of my main development focuses, so please look forward to future updates.  

   Currently supported characters:
   - Kanami (Strinova)
   - Hoshie (Strinova)

4. [CS2 Die to Play](https://github.com/sngrotesque/CS2_Die2Play)  
   A program that automatically opens Douyin when you die in a CS2 match, and switches back to the game upon respawn.  
   Supports **custom URLs** / **wallpaper switching**, etc. Built with the Flutter framework, supporting Windows.

5. [HashAll](https://github.com/sngrotesque/HashAll)  
   A file hashing tool designed to replace `xxx-sum` utilities (`sha256sum` / `md5sum`), implemented in C++ with the OpenSSL library.

6. [CopyPath](https://github.com/sngrotesque/ContextMenu_CopyPath)  
   A path-copying tool that resides in the right-click context menu. More features may be added in the future.

7. [The Wizard's Universal Key (wizard_key)](https://github.com/sngrotesque/wizard_key)  
   I worked on this project for over a year, nearly two years. It was my first serious programming project, written in C++.  
   It once carried my ambition to "do everything," but eventually I realized: "**Focusing on specific areas is more important than trying to build a universal tool.**"  
   Although it is now discontinued, it helped me grow significantly in both project management and code quality.

# 🔐 Public Key Verification

To ensure users can safely download the files I publish, I use **GPG** for signature verification.

- Fingerprint: `003CC84A9F6B10C233114C18F1E31EE85D9E0244`
- Long Key ID: `0xF1E31EE85D9E0244`

You can retrieve my public key from a [public key server](https://keys.openpgp.org/) using this information, and verify that the files you download are indeed published by me.  
In my repositories, you'll see `.asc` / `.sig` files used to verify the integrity and origin of released files.  
If you don't find these verification files, don't panic — they are only used for projects released after July 2026.

If you're not sure what this is about, no worries — it's just for confirming that the repository content was indeed written and uploaded by me. It doesn't affect your use of the projects.

# 📞 Contact

- [哔哩哔哩 / Bilibili](https://space.bilibili.com/27958784) - My video account
- [Gmail](mailto:sngrotesque@gmail.com) - My Google email address

> You might find a YouTube account by searching for `SN-Grotesque`, but I no longer maintain that account — no need to follow it.

# 🤝 Collaboration

Currently, I do not consider any form of collaboration, only commissioned work.

If you truly have a great collaboration idea, feel free to propose it to me (contact info above).