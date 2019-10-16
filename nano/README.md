# Syntax file for nano

## Getting nano

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
