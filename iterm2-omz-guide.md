# Setup iterm2 and oh-my-zsh

1. install iterm2: 
	- brew cask install iterm2

2. Get the iTerm color settings
	- Solarized Dark theme 
	https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors
	- Apply through iTerm → preferences → profiles → colors → load presets

3. install oh-my-zsh: 
	- sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

4. install pk10
	- git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

5. Edit your ~/.zshrc and set ZSH_THEME="powerlevel10k/powerlevel10k"

6. restart iterm2
