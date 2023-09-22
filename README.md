Prerequisite (for ubuntu):

sudo snap install --classic nvim # tested on nvim 0.9.1
sudo apt install ripgrep xclip cargo
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
cargo install tree-sitter-cli

After:
    nvim ~/.config/nvim/lua/i/packer.lua
    :w
    :so
    :PackerSync

