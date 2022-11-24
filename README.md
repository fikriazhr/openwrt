<p align="center">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/lynxnexy/openwrt/Build%20OpenWrt"> <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/lynxnexy/openwrt?label=commits"> <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/lynxnexy/openwrt"> </br>
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/lynxnexy/openwrt"> <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/lynxnexy/openwrt/total">
</p>

## OpenWrt 21.02
OpenWrt 21.02 for ZTE B860H and FiberHome HG680P with more packages ported, more devices supported, better performance, and special optimizations for users. Compared the official one, we allow to use hacks or non-upstreamable patches / modifications to achieve our purpose. Source from anywhere.

[<img src="https://cdn.trakteer.id/images/embed/trbtn-red-2.png" height="40" style="border:0px;height:40px;" alt="Trakteer Saya">](https://trakteer.id/lynxnexy/tip)

## Firmware information
1. Default IP: `192.168.1.1`
2. Default username: `root`
3. Default password: `passwd`
4. Default WIFI name: `LYNX`
5. Default WIFI password: `none`

## Amlogic Service
Install to EMMC: </br> Login to `OpenWrt` → `System` → `Amlogic Service` → `Install OpenWrt`

Online Update: </br> Login to `OpenWrt` → `System` → `Amlogic Service` → `Online Download Update` 

Manual Update: </br> Login to `OpenWrt` → `System` → `Amlogic Service` → `Manually Upload Update`

## Overviews
![Overviews](https://i.ibb.co/D1rSJdf/Screenshot-2022-11-24-19-07-02-760-com-android-chrome.jpg)

## Menu
![Menu](https://i.ibb.co/tp7fnm2/Screenshot-2022-11-24-19-07-10-494-com-android-chrome.jpg)

## Terminal
![Terminal](https://i.ibb.co/tbDRDnH/Screenshot-2022-11-24-19-07-28-909-com-android-chrome.jpg)

## Applications
This is a list of luci applications installed in this firmware: </br>
`luci-app-3ginfo`\
`luci-app-adblock`\
`luci-app-amlogic`\
`luci-app-aria2`\
`luci-app-atinout-mod`\
`luci-app-autoreboot`\
`luci-app-diskman` <sub>include</sub>\
&emsp;&emsp;`├─ mdadm`\
&emsp;&emsp;`├─ kmod-md-raid456`\
&emsp;&emsp;`└─ kmod-md-linear`\
`luci-app-dockerman`\
`luci-app-eqos`\
`luci-app-filetransfer`\
`luci-app-firewall`\
`luci-app-hd-idle`\
`luci-app-minidlna`\
`luci-app-openclash` <sub>include</sub>\
&emsp;&emsp;`├─ clash`\
&emsp;&emsp;`├─ clash_tun`\
&emsp;&emsp;`├─ clash_meta`\
&emsp;&emsp;`└─ v2ray-rules-dat`\
`luci-app-openvpn`\
`luci-app-opkg`\
`luci-app-passwall` <sub>include</sub>\
&emsp;&emsp;`├─ iptables_transparent_proxy`\
&emsp;&emsp;`├─ brook`\
&emsp;&emsp;`├─ chinadns_ng`\
&emsp;&emsp;`├─ haproxy`\
&emsp;&emsp;`├─ hysteria`\
&emsp;&emsp;`├─ naiveproxy`\
&emsp;&emsp;`├─ shadowsocks_libev_client`\
&emsp;&emsp;`├─ shadowsocks_libev_server`\
&emsp;&emsp;`├─ shadowsocks_rust_client`\
&emsp;&emsp;`├─ shadowsocks_rust_server`\
&emsp;&emsp;`├─ shadowsocksr_libev_client`\
&emsp;&emsp;`├─ shadowsocksr_libev_server`\
&emsp;&emsp;`├─ simple_obfs`\
&emsp;&emsp;`├─ trojan_go`\
&emsp;&emsp;`├─ trojan_plus`\
&emsp;&emsp;`├─ v2ray`\
&emsp;&emsp;`├─ v2ray_plugin`\
&emsp;&emsp;`├─ xray`\
&emsp;&emsp;`└─ xray_plugin`\
`luci-app-ramfree`\
`luci-app-rclone` <sub>include</sub>\
&emsp;&emsp;`├─ rclone-webui`\
&emsp;&emsp;`└─ rclone-ng`\
`luci-app-samba4`\
`luci-app-ssr-plus` <sub>include</sub>\
&emsp;&emsp;`├─ shadowsocks_rust_client`\
&emsp;&emsp;`├─ shadowsocks_rust_server`\
&emsp;&emsp;`├─ chinadns_ng`\
&emsp;&emsp;`├─ hysteria`\
&emsp;&emsp;`├─ ipt2socks`\
&emsp;&emsp;`├─ kcptun`\
&emsp;&emsp;`├─ naiveproxy`\
&emsp;&emsp;`├─ redsocks2`\
&emsp;&emsp;`├─ shadowsocks_simple_obfs`\
&emsp;&emsp;`├─ shadowsocks_v2ray_plugin`\
&emsp;&emsp;`├─ shadowsocksr_libev_client`\
&emsp;&emsp;`├─ shadowsocksr_libev_server`\
&emsp;&emsp;`└─ trojan`\
`luci-app-statistics`\
`luci-app-transmission`\
`luci-app-ttyd`\
`luci-app-vnstat2`\
`luci-app-wireguard`\
`luci-app-zerotier`
