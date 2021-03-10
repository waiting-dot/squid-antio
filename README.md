# squid-antio
Инструкция блокировки порно на своем компьютере в системе Ubuntu во время ломок для облегчения воздержания (проверено на Ubuntu 18.04)


1. Закрыть доступ к телефону
```
sudo chmod 750 /usr/lib/gvfs/gvfsd-mtp
sudo chmod 750 /usr/lib/gvfs/gvfsd-gphoto2
```
2. Закрыть доступ к флешкам
```
sudo chmod 750 /media
```
3. Закрыть прямой доступ к сетевой карте из virtualbox
```
sudo modprobe -r vboxnetflt
```                                 
