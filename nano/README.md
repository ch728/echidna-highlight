# Syntax file for nano (Linux)

## Getting nano
Nano is installed by defualt in most Linux distros, but if you are using some exotic distro you can download a version of nano here https://www.nano-editor.org/download.php
## Using syntax config

Create a directory in /home to store your echidna.nanorc file.

```bash
mkdir ~/.config/nano
```
Put echidna.nanorc in there and then create a .nanorc in your home directory that imports this file.

```bash
echo 'include ~/.config/nano/echidna.nanorc' >> .nanorc
```
Enjoy!
