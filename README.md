# Linux Development Utilities

## Table of Contents
- `.tmux.conf`: `tmux` configuration
- `.config/nvim`: `neovim` configuration

## Installation (WIP)
Maybe a script to install all the utilities in the future.

### Install `zsh`
```bash
sudo apt install zsh
zsh
```
### Install `oh-my-zsh`
#### Run this to install Oh My Zsh:
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
zsh
```

#### Install PowerLevel10K Theme for Oh My Zsh
Run this to install PowerLevel10K:
```bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

Now that it's installed, open the `~/.zshrc` file with your preferred editor and change the value of "ZSH_THEME" as shown below:

```bash
ZSH_THEME="powerlevel10k/powerlevel10k"
```

To reflect this change on your terminal, restart it or run this command:

```bash
source ~/.zshrc
```

Configure theme

## Reference
- iTerm2, Oh-my-zsh: 
  - https://www.youtube.com/watch?v=CF1tMjvHDRA
  - https://www.josean.com/posts/terminal-setup
- Tmux: 
  - https://www.youtube.com/watch?v=U-omALWIBos
  - https://www.josean.com/posts/tmux-setup
  - https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/
  - https://www.youtube.com/watch?v=H70lULWJeig
- Neovim:
  - https://www.youtube.com/watch?v=vdn_pKJUda8
  - https://github.com/josean-dev/dev-environment-files