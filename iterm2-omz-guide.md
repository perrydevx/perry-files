# Setup iterm2 and oh-my-zsh

*Be cool and gain +100 points coding skills by making your terminal look like this!*
![alt text](https://github.com/perrydevx/perry-files/blob/master/iterm2-omz.png)

1. **Install iterm2** 
```
brew install --cask iterm2
```
2. **Get the iTerm color settings**
    - [Solarized Dark](https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors) (Save link as...) save the file as "Solarized Dark - Patched.itermcolors"
    - Double click the file "Solarized Dark - Patched.itermcolors" to load in iterm        
    - Then apply theme in iTerm → preferences → profiles → colors → color presets (you can delete the file after doing this)

3. **Install oh-my-zsh**
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
4. **Install pk10**
```
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```
5. **Edit your ~/.zshrc and set ZSH_THEME**
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```
6. **After setting powerlevel10k as zsh_theme, restart iterm2, wizard will guide you through UI settings**

    - To reset settings 
```
p10k configure
```

## Additional plugins

- **Download zsh-autosuggestions**
```
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```
- **Download zsh-syntax-highlighting**
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```
- **Enable plugins**

vi .zshrc and modify plugins
```
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```	

## Restart iTerm2, enjoy!! :beer:

**[Use ⌥ ← and ⌥→ to jump forwards / backwards words in iTerm 2](https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x)**

