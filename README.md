## terminology  
  
DESCRIBE  
  
requires:    
apt: ```apt install terminology```  
yum: ```yum install terminology```  
pacman: ```pacman -S terminology```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/terminology/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/terminology" "$HOME/.config/terminology.bak"
git clone https://github.com/dfmgr/terminology "$HOME/.config/terminology"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/terminology" target="_blank">terminology wiki</a>  |  
  <a href="https://www.enlightenment.org/about-terminology" target="_blank">terminology site</a>
</p>  
