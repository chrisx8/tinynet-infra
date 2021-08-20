# TinyNET Infrastructure Repo

Core repo for TinyNET infrastructure config and docs.

## Hardware

### Gateway

- NETGEAR R6220
- OS: OpenWrt
- CPU: MediaTek MT7621ST (ramips)
- RAM: 128MB (Onboard)
- Storage: 128MB Onboard NAND
- Networking: 5 * GbE + 2x2 dual-band 802.11 n/ac

### Krista

- HP EliteDesk 800 G2 Mini
- OS: Proxmox VE (includes [Proxmox Backup Server](https://pbs.proxmox.com/docs/))
- CPU: Intel Core i5-6500T (AMT/vPro)
- RAM: 8GB DDR4 (1 * 8GB SODIMM)
- Storage: 240GB NVMe SSD
- Networking: 1 * GbE

## Services

### Networking / Ingress

- [OpenWrt](https://openwrt.org/)
- [NGINX](https://nginx.org)
- [WireGuard](https://www.wireguard.com/)

### IAM

- [Keycloak](https://www.keycloak.org/)
- [mod_auth_openidc](https://github.com/zmartzone/mod_auth_openidc)

### Web Apps

- [BookStack](https://www.bookstackapp.com/)
- [Firefly III](https://www.firefly-iii.org/)
- [Minflux](https://miniflux.app/)
- [Nextcloud](https://nextcloud.com/)
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- [Wiki.js](https://js.wiki/)

### Storage

- OpenSSH / SFTP
- [Proxmox Backup Server](https://pbs.proxmox.com/docs/)

## Resources

- [How to Home Lab](https://www.dlford.io/tag/how-to-home-lab-series/)
- [Postfix mail relay](https://www.howtoforge.com/tutorial/configure-postfix-to-use-gmail-as-a-mail-relay/)
- [Setting up WireGuard](https://linuxize.com/post/how-to-set-up-wireguard-vpn-on-ubuntu-20-04/)
