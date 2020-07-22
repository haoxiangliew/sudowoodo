# sudowoodo

**sudowoodo is a Pokemon, and is part of Nintendo's intellectual property. As with the [Fair Use](https://en.wikipedia.org/wiki/Fair_use) Act, it does not harm but promote their property in a reasonable way (Open Source GPLv3) and will NOT be used for profit.**

### Did you ever want to launch a elevated command prompt from WSL without going through all the steps?
* Win + X => Command Prompt (Admin)
* Win => Search for Command Prompt => Right Click runas Admin
### Adding sudowoodo to your PATH on both systems lets you summon him to the rescue!

Installation
------
**The following install steps are on Windows 10 2004 with Ubuntu 20.04 on WSL2, steps / instructions may differ depending on your system.**
1. Clone this repository.
2. Extract and/or Move `sudo.bat` and `sudowoodo.bat` to `C:/Windows/System32`, grant Administrator privileges as needed.
3. Extract and/or Move `sudowoodo` to `/usr/bin` in **WSL**
4. Enter WSL shell and `cd /usr/bin` => `sudo chmod +x sudowoodo`

The following commands in the respective shell will open a new instance of Command Prompt with Administrator Privileges
| cmd.exe | WSL |
|---------|-----|
|`sudo`   |`sudowoodo`|

5. Carefully read the words of wisdom from sudowoodo
6. Enjoy using stuff like diskpart and chocolatey from WSL!
