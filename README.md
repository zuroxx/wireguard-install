# Unattended WireGuard installer

Easily set up a dual-stack [WireGuard](https://www.wireguard.com/) VPN on a Linux server without touching the console. ©Automate the effect.

## Requirements

Supported distributions:

- Ubuntu
- Debian
- Centos

## Usage

First, get the script and make it executable :

```bash
curl -O https://raw.githubusercontent.com/zuroxx/wireguard-install/master/wireguard-install.sh
chmod +x wireguard-install.sh
```
```sh
./wireguard-install.sh
```

Credits:
https://github.com/angristan/wireguard-install


Changes: Cloudflare, Google DNS Servers set on IPv4. User input disabled.
