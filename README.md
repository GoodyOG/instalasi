## UPGRADE FOR DEBIAN AND UBUNTU
Masukkan perintah dibawah jika anda menggunakan OS Debian Version 10 atau OS Ubuntu Version 20
```
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt -y install xxd && apt install -y bzip2 && apt install -y wget && apt install -y curl && reboot
```

## INSTALL SCRIPT 
Masukkan perintah dibawah untuk menginstall Autoscript Premium
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/GoodyOG/instalasi/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```