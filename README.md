wills_vim
=========

my_vim_folder : this is setup for vim

to copy clone into ~/.vim

copy the .vimrc file into your home folder

`cp ~/.vim/.vimrc ~/.vimrc`


to add a new module I use Pathogen and I use GIT submodules to organize them, below is an example with the Vim fugitive submodule.

`$ cd ~/.vim`
`$ git submodule add git://github.com/tpope/vim-fugitive.git bundle/fugitive`
`git submodule init && git submodule update`

The last line updates all your submodules.



