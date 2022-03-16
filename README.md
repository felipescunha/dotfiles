### Install Homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### Install ZSH | macOS
```bash
brew install zsh
```
### Install ZSH | Debian & derivatives - Windows 10 WSL
```bash
apt install zsh
```
### Install Oh My ZSH
```bash
sudo sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/lukechilds/zsh-nvm ~/.oh-my-zsh/custom/plugins/zsh-nvm
rm -rf ~/.zshrc
```
### Install Zinit
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/zdharma-continuum/zinit/master/doc/install.sh)"
```
### Install NVM
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
### Setup dotfiles
```bash
git clone https://github.com/felipescunha/dotfiles.git ~/.dotfiles
cd ~/dotfiles
```
### Simbolyc links
```bash
ls -s ~/.dotfiles/.zshrc ~/zshrc
ls -s ~/.dotfiles/.gitconfig ~/.gitconfig
```
