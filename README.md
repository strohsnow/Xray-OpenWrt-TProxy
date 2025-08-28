### Prerequisites
- [xray-core](https://github.com/yichya/openwrt-xray)
- kmod-nft-socket
- kmod-nft-tproxy
- curl
### Installation
- Copy `xray` to `/etc/init.d/xray`
- Run `chmod +x /etc/init.d/xray`
- Copy `config.json` to `/etc/xray/config.json`
- Adjust `/etc/xray/config.json` accordingly
- Run `service xray update` to download geofiles
- Run `service xray start` to start xray
