# Unattended WireGuard installer

Easily set up a dual-stack [WireGuard](https://www.wireguard.com/) VPN on a Linux server with less human interaction. ©Automate the effect.

## Requirements

Supported distributions:

- Ubuntu
- Debian
- Centos
- RedHat

Still works, but attended:

- Arch
- Fedora

## Host

Prefeably a cloud host running KVM such as GCP, AWS, and Vultr (actual unlimited bandwidth), for examples. Check for the egress costs of your host. Also Azure, I switch to their, "Standard B1ls (1 vcpus, 0.5 GiB memory)" after installing on a higher resource VM, it can be a cost effective option. Digital Ocean is not recommended for a VPN due to continual DMCA disconnects from false positives. LXC & OpenVZ are not supported (yet).

## Usage

First install cURL

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


## Changes
Cloudflare, Google DNS Servers set on IPv4. User input disabled. Added RedHat support.


## Credits

https://github.com/angristan/wireguard-install
