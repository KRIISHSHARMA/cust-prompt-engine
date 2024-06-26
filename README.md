# SETTING ENV
- Make sure `$TERM` is set to `xterm-256color`
``` sh
echo $TERM
```

# Installation
- Make Choose a directory where you have write permissions. For example, you can create a directory named oh-my-posh in your home directory:
``` sh
mkdir ~/oh-my-posh
```
- Modify the installation command to use the directory you just created 
``` sh
curl -s https://ohmyposh.dev/install.sh | bash -s -- -d ~/ohmyposh
```
- Permanent PATH Update (for all sessions): Add the following line to your shell configuration file (e.g., ~/.bashrc, ~/.bash_profile, ~/.zshrc depending on your shell):
 ``` sh
export PATH=~/oh-my-posh:$PATH
```
- Install Font
``` sh
oh-my-posh font install
```

- Add the following to ~/.bashrc (could be ~/.profile or ~/.bash_profile depending on your environment):
``` sh
eval "$(oh-my-posh init bash)"
```
- Once added, reload your profile for the changes to take effect.
``` sh
exec bash
```
