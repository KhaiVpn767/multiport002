# SC MULTI VER 4 TERAKHIR
## Update & Upgrade First Your VPS for Debian 10 & 11
```
wget https://raw.githubusercontent.com/KhaiVpn767/multiport002/main/update/install_up.sh && chmod +x install_up.sh && ./install_up.sh
```


## Update & Upgrade First Your VPS for Ubuntu 18.04 & 20.04
```

wget https://raw.githubusercontent.com/KhaiVpn767/multiport002/main/up.sh && chmod +x up.sh && ./up.sh
```


## install sc
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/KhaiVpn767/multiport002/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
