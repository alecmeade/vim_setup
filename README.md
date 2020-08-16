# vim_setup
My default vim setup which uses [pathogen](https://github.com/tpope/vim-pathogen) for installing additional packages. 

## Setup
1. cd ~
2. git clone https://github.com/alecmeade/vim_setup
3. cp vim_setup/vim_files.zip vim_files.zip
4. unzip vim_files.zip
5. rm -rf .vim & rm .vimrc rm & .viminfo
6. cp -r vim_files/.vim .vim & cp vim_files/.vimrc .vimrc cp & vim_files/.viminfo .viminfo
7. rm -rf vim_files & rm -rf vim_setup

## Update
To update this vim setup, create a directory for the .vim, .vimrc and .vimrc files and zip it. Then replace [vim_files.zip](https://github.com/alecmeade/vim_setup/blob/master/vim_files.zip) with the newly updated version and push the changes.
