### Install dependencies
This config require some patched [ fonts ](https://www.nerdfonts.com/).
___
#### zsh 
Install zsh (if not installed)
```
apt install zsh
```
Switch to zsh (if not switched) You can check for which shell running by `echo $0` 
```
chsh -s /bin/zsh
```
Install config (if you already have config you need to delete that by rm -f ~/.zshrc
```
wget https://raw.githubusercontent.com/3xyz/zshrc/main/.zshrc -O ~/.zshrc
```
Install plugins
```
mkdir ~/.zsh;
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/.zsh/powerlevel10k/;
git clone https://github.com/zsh-users/zsh-autosuggestions.git ~/.zsh/zsh-autosuggestions/;
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.zsh/zsh-syntax-highlighting;
wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/plugins/command-not-found/command-not-found.plugin.zsh -O ~/.zsh/command-not-found.zsh
```
Then apply changes in .zshrc by
```
source ~/.zshrc
```
At first start plugin [powerlevel10k](https://github.com/romkatv/powerlevel10k#manual) suggest u to configure title.
