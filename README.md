> # My personal settings linux deb base:




# Interface

### Icons theme

- [Numix Square](https://github.com/numixproject)


1. `sudo add-apt-repository ppa:numix/ppa`

2. `sudo apt update`

3. `sudo apt install numix-icon-theme-square`


### **Fonts** 

For VSCode and Terminal(zsh):
- [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/JetBrainsMono)





## Terminal Custom


 ### Color Scheme 
 
 - [Gogh Color Scheme](https://mayccoll.github.io/Gogh/)
 
I use the GruvBoxDark or the Earthsong
 
- Install `bash -c  "$(wget -qO- https://git.io/vQgMr)"`
 

 ### Shell customized with [oh-my-szh](https://ohmyz.sh/)

1. Install zsh:  `sudo apt install szh`
 
2.  Make default shell: `chsh -s /bin/zsh`

### Themes/Plugins

1. Install the oh-my-szh 
  `https://ohmyz.sh/`


> ### Themes

1. On `vi ~/.zshrc` find `ZSH_THEME=`

2. Set this like this: `ZSH_THEME="agnoster"` (or "refined")


> ### Plugins

- #### [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
 
1. `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`

- #### [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)  
1. `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

2. In `vi ~/.zshrc` find `plugins=(git)`
 
3. Activate the plugins like this:  `plugins=(git zsh-autosuggestions zsh-syntax-highlighting)`
 
4. Restart terminal
 
 Ref:
 
 https://gist.github.com/dogrocker/1efb8fd9427779c827058f873b94df95




# Distros

### Pop!OS

#### Gnome Extensions:

- [FLoating Dock](https://extensions.gnome.org/extension/3730/floating-dock/)

- [Vitals](https://extensions.gnome.org/extension/1460/vitals/)

- [Volume Mixer](https://extensions.gnome.org/extension/3499/application-volume-mixer/)

##

### Mint Cinnamon

- Customizing colors in cinnamon interface. Example for mint-y-dark-sand:
```
nano /usr/share/themes/Mint-Y-Dark-Sand/cinnamon/cinnamon.css 
```
For example, black color:

Task Bar

![image](https://user-images.githubusercontent.com/57546831/161820027-1a1dd913-ea11-40c4-be4d-6b3937bb06a5.png)

Menu

![image2](https://user-images.githubusercontent.com/57546831/161820062-8a9e229f-26de-4aeb-9d67-72731db3afe3.png)
