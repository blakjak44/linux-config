# fish
``sudo apt-add-repository ppa:fish-shell/release-3``<br>
``sudo apt-get update``<br>
``sudo apt-get install fish``<br>

# nvim

<b>Install + Config:</b><br>
``sudo apt-get install neovim``<br>
``sudo rm (which vi)``<br>
``sudo ln -s /usr/bin/nvim /usr/bin/vi``<br>
``mkdir .config/nvim``<br>
``curl -L https://raw.githubusercontent.com/blakjak44/linux-config/master/init.vim > ~/.config/nvim/init.vim``<br>
``curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim``<br>
``cd ~/.config/nvim/plugged``<br>
``git clone https://github.com/Valloric/YouCompleteMe``<br>
``cd YouCompleteMe``<br>
``git submodule update --init --recursive``<br>
``sudo apt install nodejs npm``<br>
``sudo apt install build-essential cmake python3-dev``<br>
``python3 install.py --clang-completer --ts-completer``<br>
