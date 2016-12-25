# Thin GUI
---
Run just lxterminal on lxde.
Because the raw Linux terminal provided has poor customisability.

Builds on the official Raspbian Lite image (latest: jessie).

```shell
# Update repos
apt-get update
apt-get upgrade
apt-get dist-upgrade
apt-get clean

# Install Xserver and LXDE
apt-get install --no-install-recommends xserver-xorg xinit
apt-get install lxde-core lxterminal

# Clone this folder and move configuration files
mv -t .config/ openbox lxsession lxterminal
```
