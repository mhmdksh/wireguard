# Wireguard VPN
This script will automatically install and configure Wirguard VPN on your linux machine
## Usage
Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

```bash
curl -O https://raw.githubusercontent.com/mhmdksh/wireguard/main/wireguard-install.sh
chmod +x wireguard-install.sh
./wireguard-install.sh
```
## Managing Users
Manage users from the script directly by:
1. Login to your server
2. Change to wireguard script directory: `cd wireguard`
3. Run the script again: `./wireguard-install.sh`
4. The rest is self explanatory

## Android/Iphone/PC/MAC Clients
1. Download the client for you machine using this link: https://www.wireguard.com/install/
2. Scan or import the config that was created in the last step to your machine, and start using your vpn
