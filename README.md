# zsh-theme

## Output
![2](https://user-images.githubusercontent.com/82374446/153742818-8b49dfad-6805-4ac1-8eb8-d953b239d8c9.png)

## use
- run this command ```git clone https://github.com/shinqcn/cn-zsh.git && cd cn-zsh && mv cn.zsh-theme /$HOME/.oh-my-zsh/themes/```
- now open **.zshrc file** ```nano /$HOME/.zshrc```
- in **line 11** ```ZSH_THEME="cn"```
- ![1](https://user-images.githubusercontent.com/82374446/153742810-b862b759-cd41-4ca6-a3e0-6400b5889211.png)
- close terminal and reopen

---------------

## Banner

 #### 1. Install figlet and lolcat
 ```apt install figlet lolcat```
 
 #### 2. Download this script
 ```wget https://github.com/xero/figlet-fonts/blob/master/ANSI%20Shadow.flf /usr/share/figlet/```
 
 #### 3. Add this command in the end of .zshrc file
 ```figlet -ct -f 'ANSI Shadow' YOURNAME | lolcat```
 
 #### 4. Set alias in end of .zshrc File
 ```nano ~/.zshrc```  
 ```alias clear="clear && figlet -ct -f 'ANSI Shadow' YOURNAME | lolcat"```
