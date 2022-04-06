# my-linux-config
## My personal linux deb base configs settings:



> # Interface

- **Icons theme**

https://github.com/numixproject/ (I use Numix Square)



- **Fonts** 

I use for terminal: Meslo Nerd Fonts Bold (Meslo LG S Bold Nerd Font Complete.ttf) 
https://www.nerdfonts.com/font-downloads


I use for VSCode: Cascadia Code Bold
https://github.com/microsoft/cascadia-code



--------------------------------------------


> # Terminal Custom

- Color Scheme 
 
 I like the [Gogh Color Scheme](https://mayccoll.github.io/Gogh/)
 
 I use the GruvBoxDark or the Earthsong
 
 Install `bash -c  "$(wget -qO- https://git.io/vQgMr)"`


## 

### Shell customized with zsh

- Install zsh:  `sudo apt install szh`
 
 Make default shell: `chsh -s /bin/zsh`

### Themes with oh-my-szh

- Install the oh-my-szh 
  `https://ohmyz.sh/`

Config theme:

On `nano ~/.zshrc` find `ZSH_THEME=`

Set this like this: `ZSH_THEME="agnoster"` (or "refined")

##
 
### Plugins

 - zsh-autosuggestions (auto complete) / - zsh-syntax-highlighting
 
run `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`
  
and `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

On `nano ~/.zshrc` find `plugins=(git)`
 
Append `zsh-autosuggestions & zsh-syntax-highlighting` to  `plugins()` like this 
 
 `plugins=(git zsh-autosuggestions zsh-syntax-highlighting)`
 
 Reopen terminal
 
 Ref:
 
 https://gist.github.com/dogrocker/1efb8fd9427779c827058f873b94df95

-----------------------------------------------

> # Distros

### Pop!OS

- Gnome Extensions:

[FLoating Dock](https://extensions.gnome.org/extension/3730/floating-dock/)

[Vitals](https://extensions.gnome.org/extension/1460/vitals/)

[Volume Mixer](https://extensions.gnome.org/extension/3499/application-volume-mixer/)

##

### Mint Cinnamon

Customizing colors in cinnamon interface. Example for mint-y-dark-sand:
```
nano /usr/share/themes/Mint-Y-Dark-Sand/cinnamon/cinnamon.css 
```
For example, black color:

Task Bar

![image](https://user-images.githubusercontent.com/57546831/161820027-1a1dd913-ea11-40c4-be4d-6b3937bb06a5.png)

Menu

![image2](https://user-images.githubusercontent.com/57546831/161820062-8a9e229f-26de-4aeb-9d67-72731db3afe3.png)
