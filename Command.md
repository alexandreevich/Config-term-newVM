# Command
## Commands for beautiful terminal 
1. sudo apt install zsh
2. apt install curl
3. sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
4. git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
6. git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
7. git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
8. nano ~/.zshrc   and add ZSH_THEME="powerlevel10k/powerlevel10k" POWERLEVEL9K_MODE="nerdfont-complete" plugins=(git zsh-syntax-highlighting) 
9. p10k configure
10. nano ~/.p10k.zsh and add : 
11. for i in {0..255}; do print -Pn \"%K{$i}  %k%F{$i}${(l:3::0:)i}%f \" ${${(M)$((i%6)):#3}:+$'\n'}; 

## Done
