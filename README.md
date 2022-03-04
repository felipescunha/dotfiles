### Install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Install ZSH | macOS
brew install zsh

### Install ZSH | Debian & derivatives - Windows 10 WSL
apt install zsh

### Install Oh My ZSH
sudo sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"\
git clone https://github.com/lukechilds/zsh-nvm ~/.oh-my-zsh/custom/plugins/zsh-nvm\
rm -rf ~/.zshrc

### Install Zinit 
sh -c "$(curl -fsSL https://raw.githubusercontent.com/zdharma-continuum/zinit/master/doc/install.sh)"

### Setup dotfiles
git clone https://github.com/felipescunha/dotfiles.git ~/.dotfiles\
cd ~/dotfiles\
ls -s ~/.dotfiles/.zshrc ~/zshrc\
ls -s ~/.dotfiles/.gitconfig ~/.gitconfig


