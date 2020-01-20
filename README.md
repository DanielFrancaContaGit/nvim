# Configuração do NVIM e plugins

1 - Instale a versão mais recente:
```
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt-get update
sudo apt-get install neovim
```

2 - Clone este repositório:
```
cd ~/.config
git clone https://github.com/jrmmendes/nvim
```

3 - Instale o FZF:
```
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

4 - Instale o vim-plug:
```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

5 - Instale os plugins com o VimPlug. Abra o nvim e execute:
```
:PlugInstall
```
