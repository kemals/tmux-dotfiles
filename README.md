# tmux-dotfiles

[!tmux](https://i.imgur.com/vrthUBC.png)
## Prerequisites

1. [tmux](https://github.com/tmux/tmux/wiki) (2.5)
1. [Python](https://www.python.org/) (this documentation is assuming Python3 is installed even though setup would be working with minor modifications with Python 2.7) 
2. [powerline](http://powerline.readthedocs.io/en/master/installation.html), awesome statusline for vim and couple of several other awesome applications
3. [Tmux Better Mouse Mode](https://github.com/NHDaly/tmux-better-mouse-mode), tmux plugin to better manage your mouse

## Setup

1. Clone this repo:
```
git clone https://github.com/kemals/tmux-dotfiles
```
2. Backup current configuration file, if you have one:
```
cp ~/.tmux.conf ~/.tmux.conf.bac
```
3. Copy cloned config file as new .tmux.conf:
```
cp tmux-dotfiles/config/tmux.conf ~/.tmux.conf
```
4. In case you don't have powerline installed, install it with:
```
pip install powerline-status
```
5. In case you don't have Tmux Better Mouse Mode plugin installed, install it with:
```
cd ~/Documents
git clone https://github.com/NHDaly/tmux-better-mouse-mode
```
6. Start tmux and profit!
```
tmux
```

## Shortcuts

tmux.conf already containts some of the relevant shortcuts documented, but this [cheat sheet](https://tmuxcheatsheet.com/) contains a lot of useful information!

1. < CTRL b > < CTRL b > - Go to previous window
2. < CTRL b > < CTRL k > - Clear history
3. < CTRL b > < r > - Reload tmux
4. < CTRL b > < P > - Save content of buffer to the file
5. < CTRL b > < Escape > - Enter 'copy' mode
In 'copy' mode: use vim shortcuts
In 'copy' mode: press 'v' to start selection
In 'copy' mode: press 'y' to copy selected
6. < CTRL b > < p > - paste content of the buffer
7. < CTRL b > < c > - create new window
8. < CTRL b > < , > - rename window
9. < CTRL b > < " > - horizontal split
10. < CTRL b > < % > - vertical split
