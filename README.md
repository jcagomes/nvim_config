## Configure nvim
install chrome
install scroll reverser
`axes vertical 
devices mouse`
### install docker 
### install vscode
-docker
-jupyter
-markdown preview mermaid
-pylance
-remote containers
-python
-mateiral icon theme
color: tomorrow night blue
icon; material icon

### install iterm2
install ohmyzsh - https://github.com/ohmyzsh/ohmyzsh
### nvim_config
install homebrew - /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install rectangle
brew install pyenv
Run zsh commands in - https://github.com/pyenv/pyenv
brew install openssl readline sqlite3 xz zlib tcl-tk
pyenv install 3.10.1
pyenv global 3.10.1 
python --version
pip install -U pynvim
pip install 'python-lsp-server[all]' pylsp-mypy pyls-isort
`install node.js`
npm install -g vim-language-server
brew install ctags
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font
brew install neovim
python -m pip install -U autopep8
python -m pip install --upgrade pip
pip install -U pynvim
pip install 'python-lsp-server[all]' pylsp-mypy pyls-isort
pip install vim-vint
pip install pylint
pip install flake8
brew install ripgrep
git clone --depth=1 https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/opt/packer.nvim
cd ~/.config/nvim
rm -rf .* && rm -rf *
git clone --depth=1 https://github.com/jdhao/nvim-config.git .
open nvim and run :PackerSync
vi ~/.config/nvim/core/themes.vim
change line let s:theme = utils#RandElement(keys(s:theme2dir))
to line let s:theme = "kanagawa"
add the following 2 lines to ./config/nvim/init.vim to add F9 execute python files: 
autocmd FileType python map <buffer> <F9> :w<CR>:exec '!python3' shellescape(@%, 1)<CR>
autocmd FileType python imap <buffer> <F9> <esc>:w<CR>:exec '!python3' shellescape(@%, 1)<CR>

dock
---
right click dock and choose auto hide


mac
---
Preferences -> keyboard - > F keys are standard F keys. remove world key as nothing

signcolumn
--
vi ~/.config/nvim/core/options.vim | set to signcolumn:yes:2 
