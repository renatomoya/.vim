# How to install

(Re)move ~/.vim and ~/.vimrc if you have them already, and run:

    cd ~/
    git clone git@github.com:renatomoya/.vim.git
    cd ~/.vim
    git submodule update --init
    ln -s ~/.vim/vimrc ~/.vimrc

# How to update

As long as your checkout is kept clean, you can easily update, rebase your local changes and update submodules with:

    cd ~/.vim && git pull --rebase ; git submodule update ; cd -
