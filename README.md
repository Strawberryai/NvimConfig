# Introduction
These are my [NeoVim](https://neovim.io/) configuration files. It includes my
keybinds and plugins wich makes programming on the terminal more enjoyable.

# Installation
To install NeoVim with this configuration follow these commands (on a Unix like
system):

Install neovim (apt):
```
sudo apt install neovim
```

Install [vim-plug](https://github.com/junegunn/vim-plug):
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \ https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Install [nodejs]() for coc completion:
```
curl -sL install-node.vercel.app/lts | bash
```

Set up the config files:
```
mkdir ~/temp && cd ~/temp
git clone https://github.com/Strawberryai/NvimConfig
cp -r NvimConfig/nvim ~/.config
rm -rf ~/temp
nvim #And inside vim make :PlugInstall
```
