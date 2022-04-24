# nvim.config
Configuração do NVIM ~/.config/nvim/init.nvim

# Setting up Vim-Plug

> curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    
# It needs a new version of NodeJS

curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt-get install -y nodejs

(This is the new version of the time)
    
# Setting up plugins

No Neovim terminal:

PlugInstall

# Updating the plugins

No Neovim terminal:

PlugUpdate

# NERDTree Setup

It needs Nerd Fonts installed on the system.
