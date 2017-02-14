OpenWrt repository for vlmcsd
========
Binaries built from this repository on 2017-02-14 can be downloaded from http://cokebar.github.io/openwrt-vlmcsd/.
To install the vlmcsd package, run
```
echo "src/gz announce http://cokebar.github.io/openwrt-vlmcsd/OpenWrt" >> /etc/opkg.conf
opkg update
opkg install vlmcsd
```
