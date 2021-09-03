# Config-zsh

## Installation

* Make sure [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh/) has been installed.

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

* Clone plugins:

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

* Copy `.zshrc` into the right location. Default location is `~/.zshrc`

```bash
curl https://raw.githubusercontent.com/cnliusen/config-zsh/master/.zshrc > ~/.zshrc
```
