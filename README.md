# My Linux Setup (Ubuntu)

Hi! I'm **Dabananda Mitra**. I am sharing my Linux setup files and procedures here. 


# Terminal: Bash to ZSH

 1. Install zsh
 ```sudo apt install zsh```
 2. Change shell
 ```chsh```
 3. Set shell to **zsh**
 ```/bin/zsh```
 4. Logout and login or restart computer
 5. Install **oh my zsh**
 ```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```
 6. Install **powerlevel10k** theme
 ```git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k```
 7. Download and install the fonts from the repository
 ```https://github.com/dabananda/my-linux-setup/tree/main/powerline-fonts```
 8. Install **gnome tweaks**
 ```sudo apt install gnome-tweaks```
 9. Open **gnome tweaks** and select **Fonts** tab and then select **MesloLGS NF Regular** as **Monospace text**
 ```gnome tweaks > Fonts > Monospace text: MesloLGS NF Regular```
 10.   Edit theme by entering the below command on the terminal
 ```gedit ~/.zshrc```
 11. **zshrc** file will be opened. Set the **ZSH_THEME** theme to **powerlevel10k/powerlevel10k"**
 ```ZSH_THEME="powerlevel10k/powerlevel10k"```
 12. Now close the terminal and open again to configure the **zsh** terminal. That's it.
