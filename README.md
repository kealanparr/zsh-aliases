# zsh-aliases

https://linuxhint.com/configure-use-aliases-zsh/
^ How to exit nano. Ctrl, X. Press Y to save and then press enter to save where it currently is.

## npm
Insert all company specific ones for where you work

# Docker 
t = travel to my most commonly used package (normally when using Lerna)   
tb = take me back to top level of code repo     

# git

## git aliases
git config --global alias.p "!git pull origin \"$(git symbolic-ref --short HEAD)\" # this will now work for main and master, not just 1 of em
git config --global alias.co checkout   
git config --global alias.b branch  
git config --global alias.st status  
git config --global alias.wipe clean -fdx  

### stash cheatsheet

git stash  
git stash pop  
git stash apply  
git stash list  
git stash show  

Remove stash at index  
git stash pop stash@\{1\}

show whats in stash  
git stash show -p  

# general
cls = clear
