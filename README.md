# dotfile repo

## dot.zshrc

1. 安装 zsh 和 stow: `brew install zsh`
1. 配置 zsh 为默认 sh: `chsh -s $(which zsh)`
1. 安装字体, 使用 brew 需要 tap caskroom/fonts: `brew tap caskroom/fonts; brew cask install font-sourcecodepro-nerd-font`
1. git clone repo: `git clone https://github.com/laserx/dotfile.git ~/.dotfile`
1. 在项目目录中执行 `stow zsh`
1. 开启一个新的 `iterm2` 的会话, 确认安装插件

**注意**: iterm2 配置字体为 `Sauce Code Pro Nerd Font Complete`, colors schemes 配置为 [Solarized Dark Higher Contrast.itermcolors](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/schemes/Solarized%20Dark%20Higher%20Contrast.itermcolors)
