# Unattended WireGuard installer

Easily set up a dual-stack [WireGuard](https://www.wireguard.com/) VPN on a Linux server with less human interaction. ©Automate the effect.

## Requirements

Supported distributions:

- Ubuntu
- Debian
- Centos

Still works, but attended:

- Arch
- Fedora

## Host

Prefeably a cloud host running KVM such as GCP, AWS, Vultr. Check for the egress costs of your host. Digital Ocean is not recommended for a VPN due to continual DMCA disconnects from false positives.

## Usage

root User:

(1) get the script (2) make it executable (3) execute :

```bash
curl -O https://raw.githubusercontent.com/zuroxx/wireguard-install/master/wireguard-install.sh && chmod +x wireguard-install.sh && ./wireguard-install.sh
```

sudo User:

(1) get the script (2) make it executable (3) execute :

```bash
curl -O https://raw.githubusercontent.com/zuroxx/wireguard-install/master/wireguard-install.sh && sudo chmod +x wireguard-install.sh && sudo ./wireguard-install.sh
```

## Credits

https://github.com/angristan/wireguard-install


## Changes
Cloudflare, Google DNS Servers set on IPv4. User input disabled.
