# ArchsetupforGaming
arch users that wants game on they own pc<br/>
Apps use in this<br/>
[lutris](https://lutris.net/about) <br/>
[Wine](https://www.winehq.org/about) <br/>
[Gamemode](https://github.com/FeralInteractive/gamemode) <br/>
### how do we do it?
This is how. First install these packages (vulkan drivers & dependencies)<br/>
wine dependcies
```
sudo pacman -S --needed giflib lib32-giflib libpng lib32-libpng libldap lib32-libldap gnutls lib32-gnutls \
mpg123 lib32-mpg123 openal lib32-openal v4l-utils lib32-v4l-utils libpulse lib32-libpulse libgpg-error \
lib32-libgpg-error alsa-plugins lib32-alsa-plugins alsa-lib lib32-alsa-lib libjpeg-turbo lib32-libjpeg-turbo \
sqlite lib32-sqlite libxcomposite lib32-libxcomposite libxinerama lib32-libgcrypt libgcrypt lib32-libxinerama \
ncurses lib32-ncurses ocl-icd lib32-ocl-icd libxslt lib32-libxslt libva lib32-libva gtk3 \
lib32-gtk3 gst-plugins-base-libs lib32-gst-plugins-base-libs vulkan-icd-loader lib32-vulkan-icd-loader
```
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
## Apps
We need the apps that use for games and steam etc, (install these)<br/>
```
sudo pacman -S lutris wine-stating gamemode
```
### Final Step 
U have complete everything now all you need is games, How u may wonder simple gog steam etc that all basicly
### discord 
[lutris](https://discord.gg/7XzwhDcqrq) <br/>
[My discord server](https://discord.gg/Ck6JmH3D2Y)
### Screenshots
![Screenshot from 2023-09-22 04-04-34](https://github.com/Th3MaKer/ArchsetupforGaming/assets/130626103/b96522e8-0a0c-414f-9518-73414e04b6bf)
![Screenshot from 2023-09-22 16-36-05](https://github.com/Th3MaKer/ArchsetupforGaming/assets/130626103/87133dbe-97e4-4e62-b5ab-fe1d90382d42)
![Screenshot from 2023-09-23 02-55-38](https://github.com/Th3MaKer/ArchsetupforGaming/assets/130626103/8409a701-08ab-4f17-b95a-ab9386dc26ea)
![Screenshot from 2023-09-23 02-56-21](https://github.com/Th3MaKer/ArchsetupforGaming/assets/130626103/6253f82d-21e0-4e63-acea-2aefb5c69e7d)
