# Command
## Commands for beautiful terminal 
1. sudo apt install zsh
2. sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
3. git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
4. Go to file ~/.zshrc and add: plugins=(git zsh-syntax-highlighting) 
5. git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
6. nano ~/.zshrc   and add ZSH_THEME="powerlevel10k/powerlevel10k" POWERLEVEL9K_MODE="nerdfont-complete"
7. p10k configure
8. nano ~/.p10k.zsh and add : 
9. for i in {0..255}; do print -Pn \"%K{$i}  %k%F{$i}${(l:3::0:)i}%f \" ${${(M)$((i%6)):#3}:+$'\n'}; 

## Done
