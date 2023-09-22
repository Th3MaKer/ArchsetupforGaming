# ArchsetupforGaming
arch users that wants game on they own pc<br/>
Apps use in this<br/>
[lutris](https://lutris.net/about)<br/>
[Wine](https://www.winehq.org/about)<br/>
[Gamemode](https://github.com/FeralInteractive/gamemode)<br/>
### how do we do it?
This is how. First install these pkg (vulkan drivers)<br/>
intel
```
sudo pacman -S --needed lib32-mesa vulkan-intel lib32-vulkan-intel vulkan-icd-loader lib32-vulkan-icd-loader
``` 
amd
```
sudo pacman -S --needed lib32-mesa vulkan-radeon lib32-vulkan-radeon vulkan-icd-loader lib32-vulkan-icd-loader
```
nvidia
```
sudo pacman -S --needed nvidia-dkms nvidia-utils lib32-nvidia-utils nvidia-settings vulkan-icd-loader lib32-vulkan-icd-loader
```
### Apps
we need apps that has wine use for games and steam etc, (install these)<br/>
```
sudo pacman -S lutris wine-stating gamemode 
```
