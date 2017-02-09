# Shadowsock automatic installer

## ShadowsockR_installer
OS: CentOS, Debian, Ubuntu

RAM >= 128 MB

### Default Settings

> Port: 8989
> 
> Password: doufu.ru
> 
> Method: chacha20
> 
> Protoco: origin
> 
> Protocol param: 
> 
> Obfs: http_simple_compatible
> 
> Obfs param: bing.com,microsoft.com,live.com,outlook.com

### Usage
#### Install
```
bash -c "$(wget --no-check-certificate https://github.com/benzBrake/shadowsocks_installer/raw/master/shadowsocksR_installer.sh -O -)" -c "-i"
```
#### Uninstall
```
bash -c "$(wget --no-check-certificate https://github.com/benzBrake/Shell_Collections/raw/master/shadowsocksR_installer.sh -O -)" -c "-u"
```