# hassio.script.test

Test script based on https://github.com/Kanga-Who/home-assistant/blob/master/hassos_install.sh

To test if can remove prompt for installation via ansible

## Instructions

```bash
apt-get install -y software-properties-common apparmor-utils apt-transport-https avahi-daemon ca-certificates curl dbus jq network-manager

systemctl disable ModemManager

systemctl stop ModemManager

curl -fsSL get.docker.com | sh

curl -sL "https://raw.githubusercontent.com/Kanga-Who/home-assistant/master/supervised-installer.sh" | bash -s
```

## Working ?

- [x] Yes
