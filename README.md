# oh my zsh!

## Prerequisite
```bash
sudo apt install fonts-powerline git zsh
```

## Oh my zsh installation
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Plugins instalation:
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Add into your .zshrc file, the two new plugins
```bash
nano ~/.zshrc
```
```bash
plugin = (
...
zsh-autosuggestions
zsh-syntax-highlighting
)
```

## Suggested themes:
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
```bash
ZSH_THEME="agnoster"
```
