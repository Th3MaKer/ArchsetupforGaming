# ArchsetupforGaming
arch users that wants gaming on they own pc 
### how do we do it?
this is how first install these pkg(vulkan drivers)<br/>
intel
```
sudo pacman -S --needed lib32-mesa vulkan-intel lib32-vulkan-intel vulkan-icd-loader lib32-vulkan-icd-loader
``` <br/>
amd
```
sudo pacman -S --needed lib32-mesa vulkan-radeon lib32-vulkan-radeon vulkan-icd-loader lib32-vulkan-icd-loader
```
