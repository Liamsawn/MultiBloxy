> [!IMPORTANT]
> This is a fork of MultiBloxy to fix it's functionality. MAY TRIGGER BYFRON USE WITH CAUTION!
> You'll have to join through the website. I'm unsure if it's just Fishstrap, but recommended to join through Roblox.com

> Roblox is actively blocking multi-instance tools - MultiBloxy may not work for you.

# MultiBloxy 🎮🔓

<img align="right" src="https://raw.githubusercontent.com/Liamsawn/MultiBloxy/refs/heads/main/MultiBloxy/Resources/MultiBloxy.ico" />

MultiBloxy is a Windows system tray icon application designed to manage and control multiple Roblox instances. It provides a convenient way to open multiple instances for different accounts and offers a variety of options to manage them efficiently.

[![License][shield-repo-license]][repo-license]
[![Downloads][shield-repo-releases]][repo-releases]
[![Version][shield-repo-latest]][repo-latest]
[![Stars][shield-repo-stargazers]][repo-stargazers]
[![Issues][shield-repo-issues]][repo-issues]
[![Pulls][shield-repo-pulls]][repo-pulls]
[![Forks][shield-repo-forks]][repo-forks]

## Key Features 🌟
- No installation needed with a single file executable.
- Runs in the background with quick access via a system tray icon.
- Supports multiple languages.
- Easily pause and resume mutex with advanced control.
- Shows actions if Roblox is already open and can remember your choice.
- Uses about 3 MB of RAM and 0% CPU.
- Configurable settings saved in the same folder as the .exe file.
- Works with both Bloxstrap and the original bootstrapper.

## Getting Started 🚀
1. Download the `MultiBloxy.exe` from the [latest release](https://github.com/Liamsawn/MultiBloxy/releases).
2. To ensure MultiBloxy starts automatically with Windows, click <kbd>Win</kbd> + <kbd>R</kbd>, run the path `%ALLUSERSPROFILE%\Microsoft\Windows\Start Menu\Programs\StartUp`, and drop the `MultiBloxy.exe` file here.
3. Launch `MultiBloxy.exe`.
### For more detailed instructions see [GETTING_STARTED.md](https://github.com/Liamsawn/MultiBloxy/blob/main/GETTING_STARTED.md)

## How It Works ⚙️
Roblox uses a handle named `TermSrvReadyEvent` to ensure that only one instance of the game is running at a time. MultiBloxy creates this handle before Roblox does, allowing you to run as many instances of Roblox as you want.

## Is This a Virus? 🛡️
MultiBloxy is completely safe and not a virus. If you encounter a "Windows Protected Your PC" message, it appears because the application is unsigned, and obtaining a certificate can be costly. You can safely ignore it and run the program anyway. Here's how:

1. **Click on "More info"** in the warning message.
2. **Click on "Run anyway"** to proceed with running MultiBloxy.

For those who are still skeptical, you can compile the program yourself using [Visual Studio Community](https://visualstudio.microsoft.com/vs/). Alternatively, you can decompile the current executable file to ensure that it is completely safe.

## Is This Bannable? 🚫
As long as you don't use MultiBloxy to break Roblox's Term's of Service, you should be fine, however with the existence of Byfron, this fork may trigger it.

## Contributing 🤝
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please [open an issue](https://github.com/Liamsawn/MultiBloxy/issues) or [submit a pull request](https://github.com/Liamsawn/MultiBloxy/pulls).

If you want to contribute to localization, you can add new translations or improve existing ones. The localization code is located in the [Localization.cs](https://github.com/Liamsawn/MultiBloxy/blob/main/MultiBloxy/Localization.cs) file. Feel free to add new languages or correct any mistakes.

## License 📜
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using MultiBloxy! 😊

[shield-repo-license]: https://img.shields.io/github/license/Liamsawn/MultiBloxy?style=flat&labelColor=c80064&color=c80064
[repo-license]: https://github.com/Liamsawn/MultiBloxy/blob/main/LICENSE

[shield-repo-releases]: https://img.shields.io/github/downloads/Liamsawn/MultiBloxy/total?style=flat&labelColor=007ec6&color=007ec6
[repo-releases]: https://github.com/Liamsawn/MultiBloxy/releases

[shield-repo-latest]: https://img.shields.io/github/v/release/Liamsawn/MultiBloxy?style=flat&labelColor=4c1&color=4c1
[repo-latest]: https://github.com/Liamsawn/MultiBloxy/releases/latest

[shield-repo-stargazers]: https://img.shields.io/github/stars/Liamsawn/MultiBloxy?style=flat&labelColor=ffd700&color=ffd700
[repo-stargazers]: https://github.com/Liamsawn/MultiBloxy/stargazers

[shield-repo-issues]: https://img.shields.io/github/issues/Liamsawn/MultiBloxy?style=flat&labelColor=ff4500&color=ff4500
[repo-issues]: https://github.com/Liamsawn/MultiBloxy/issues

[shield-repo-pulls]: https://img.shields.io/github/issues-pr/Liamsawn/MultiBloxy?style=flat&labelColor=8a2be2&color=8a2be2
[repo-pulls]: https://github.com/Liamsawn/MultiBloxy/pulls

[shield-repo-forks]: https://img.shields.io/github/forks/Liamsawn/MultiBloxy?style=flat&labelColor=00008b&color=00008b
[repo-forks]: https://github.com/Liamsawn/MultiBloxy/network/members
