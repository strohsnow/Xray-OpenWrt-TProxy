### Prerequisites
- [xray-core](https://github.com/yichya/openwrt-xray)
- kmod-nft-socket
- kmod-nft-tproxy
- curl
### Installation
- Copy `config.json` to `/etc/xray/config.json`
- Adjust `/etc/xray/config.json` accordingly
- Copy `xray` to `/etc/init.d/xray`
- Adjust `LAN_SUBNETS_*` in `/etc/init.d/xray` accordingly
- Run `chmod +x /etc/init.d/xray`
- Run `service xray update` to download geofiles
- Run `service xray start` to start xray
