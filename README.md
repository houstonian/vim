# vim
# from https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/
Vim Configuration for Python

sudo apt-get update
sudo apt-get install git

git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim


# Adds .vimrc to your home directory since it is not there in most Ubuntu distributions
touch ~/.vimrc

vim .vimrc  (I will add final .vimrc file here)

#add to .vimrc file (CUSTOMIZATIONS)


#The following is recommended for YouCompleteMe#


sudo apt-get install build-essential cmake

sudo apt-get install python-dev python3-dev

cd ~/.vim/bundle/YouCompleteMe

DID NOT WORK FOR ME  ./install.py --clang-completer --omnisharp-completer --gocode-completer --tern-completer --racer-completer
./install.py --clang-completer --omnisharp-completer --gocode-completer
 
  ./install.py --clang-completer --gocode-completer
 
npm install -g typescript

