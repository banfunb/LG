##安装过程
###需要先给termuxAPP所有文件访问权限
## termux 输入以下命令
#⚠️有Y选Y
#⚠️不管你之前有没有执行过以下命令，现在都必须执行
```
dpkg --configure -a
```
```
apt upgrade 
```
```
pkg install git 
```
```
pkg install libc++-dev 
```
```
pkg install libc++ -y 
```
```
pkg install python 
```
```
pip install colorama 
```
```
pkg update && pkg upgrade 
```
```
pkg install mplayer  
```
```
apt install mpv 
```
```
rm -rf $HOME/LG
```
```
git clone -b main https://github.com/banfunb/LG.git
```
```
(以上步骤建议打开VPN执行命令，否则无法下载LG文件)
```
```
cd LG
```
```
chmod +x lg
chmod +x setup
chmod +x 授权777.sh
./授权777.sh
```
```
 ./lg
```
```
   ⚠️首次使用请搭建环境
```
## Start code （下次启动）
```
  [直接输入lg]
```
## 一键下载
```
dpkg --configure -a && pkg update && pkg upgrade -y && pkg install -y git python mplayer mpv && pip install colorama && rm -rf $HOME/LG && git clone -b main https://github.com/banfunb/LG.git && cd LG && chmod +x lg && chmod +x setup && chmod +x 授权777.sh && ./授权777.sh && ./lg