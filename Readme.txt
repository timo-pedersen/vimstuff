https://medium.com/@paulodiovani/installing-vim-8-plugins-with-the-native-pack-system-39b71c351fea

Instructions:

Vim plugin X in category {vendor} is under 
"~/.vim/pack/{vendor}/start/x" - autostart
"~/.vim/pack/{vendor}/opt/x" - manual loading

To add a package use e.g:
git submodule add https://github.com/preservim/nerdtree.git util/start/NERDTree
git submodule add https://github.com/vim/colorschemes.git looks/start/colorschemes
git submodule add https://github.com/morhetz/gruvbox.git looks/start/gruvbox
git submodule add https://github.com/vim-airline/vim-airline looks/start/vim-airline
git submodule add https://github.com/vim-airline/vim-airline-themes looks/start/vim-airline-themes
git submodule add https://github.com/luochen1990/rainbow.git looks/start/rainbow
git submodule add https://github.com/tpope/vim-fugitive.git tpope/start/vim-fugitive

fzf - installed on system with "winget install fzf"
git submodule add https://github.com/junegunn/fzf.vim.git util/start/fzf

This is a pack of PowerLine fonts, ONE of which is used by air-line
git submodule add https://github.com/powerline/fonts.git misc/fonts
warning: adding embedded git repository: misc/fonts

