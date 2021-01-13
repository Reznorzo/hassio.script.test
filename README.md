# hassio.script.test

Test script based on https://github.com/Kanga-Who/home-assistant/blob/master/hassos_install.sh

To test if can remove prompt for network manager modification, so that us installation script via ansible

## Instructions

```bash
apt-get install -y software-properties-common apparmor-utils apt-transport-https avahi-daemon ca-certificates curl dbus jq network-manager

systemctl disable ModemManager

systemctl stop ModemManager

curl -fsSL get.docker.com | sh

curl -sL "https://raw.githubusercontent.com/Reznorzo/hassio.script.test/main/hassio.sh" | bash -s
```

## Working ?

- [x] Yes
