## terminology  
  
Terminology is a terminal emulator for Linux/BSD/UNIX systems  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/terminology/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install terminology
```  

Fedora Based:

```shell
yum install terminology
```  

Arch Based:

```shell
pacman -S terminology
```  

MacOS:  

```shell
brew install terminology
```
  
```shell
mv -fv "$HOME/.config/terminology" "$HOME/.config/terminology.bak"
git clone https://github.com/dfmgr/terminology "$HOME/.config/terminology"
```
  
<p align=center>
  <a href="https://www.enlightenment.org/about-terminology" target="_blank" rel="noopener noreferrer">terminology site</a>
</p>  
