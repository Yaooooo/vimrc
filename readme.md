### My vim config

```sh
curl -L bit.ly/1Ac5ZEw|sh (not in China or VPN)
curl -L https://raw.githubusercontent.com/lxxdn/vimrc/master/install.sh|sh (in China without VPN)
```

Then launch vim and tap the following command
```sh
:PluginInstall
```

The only thing difficult is to install YouCompleteMe(Autocomplet plugin)

[click here](https://github.com/Valloric/YouCompleteMe) for installation details

## Install Ctags

```sh
sudo apt-get install ctags
```

## Install YouCompleteMe for C Programming (Ubuntu)

```sh
sudo apt install build-essential cmake
cd ~/.vim/bundle/YouCompleteMe
python3 install.py --clangd-completer
```


