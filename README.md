## ytdml  
  
A simple script to get songs from youtube in mp3 format with all tags from itunes  
  
  
requires:    
apt: ```apt install ffmpeg python3-pip```  
yum: ```yum install ffmpeg python3-pip```  
pacman: ```pacman -S ffmpeg python-pip``` 
  
PIP Package  
```sudo -H pip3 install --upgrade ytmdl```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/ytmdl/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/ytmdl" "$HOME/.config/ytmdl.bak"
git clone https://github.com/dfmgr/ytmdl "$HOME/.config/ytmdl"
```
  
  
<p align=center>
  <a href="https://github.com/deepjyoti30/ytmdl" target="_blank">ytmdl site</a>
</p>  
