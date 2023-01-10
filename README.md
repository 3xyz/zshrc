### Install dependencies
#### zsh 
Install zsh
```
apt install zsh
```
Switch to zsh
```
chsh -s /bin/zsh
```
Install config
```
wget https://raw.githubusercontent.com/3xyz/zshrc/main/.zshrc -O ~/.zshrc
```
Install plugins
```
mkdir ~/.zsh &&
git clone https://github.com/zsh-users/zsh-autosuggestions.git ~/.zsh/zsh-autosuggestions/ &&
wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/plugins/command-not-found/command-not-found.plugin.zsh -O ~/.zsh/command-not-found.zsh
```
