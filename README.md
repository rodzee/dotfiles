## The files are been managed by [GNU Stow](https://www.gnu.org/software/stow/)

### Installation
```
  brew install stow
```
### Setup
```
  mkdir ~/.dotfiles && cd ~/.dotfiles
```

**Copy all dotfiles to this directory as they are in your system**
*e.g. .dotfiles/tmux.conf will put the file at your parent dir (~/)*

### Use
```
  stow .
```
*to symlink the files*

### Unlink
```
  stow -D .
```
*this will remove all symlinks*
