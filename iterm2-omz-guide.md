# Setup iterm2 and oh-my-zsh

*Be cool and gain +100 points coding skills by making your terminal look like this!*
![alt text](https://github.com/perrydevx/perry-files/blob/master/iterm2-omz.png)

1. **Install iterm2** 
```
brew cask install iterm2
```
2. **Get the iTerm color settings**
    - Solarized Dark theme, save the file "Solarized Dark - Patched.itermcolors" and double click to load in iTerm
    ```
    [Solarized Dark][https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors]
    ```
    - Apply through iTerm → preferences → profiles → colors → color presets (you can delete the file after loading)

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
6. **After setting powerlevel10k as zsh_theme, restart iterm2, wizard will guide you for all UI settings**


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

vi .zshrc and modify plugins=()
```
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```	
## Restart iTerm2, enjoy!! :beer:
