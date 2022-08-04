# icinga_arm64

Unofficial repository for icinga2 packages for debian/arm64 platform.


## Use the repository
```bash
sudo apt update
sudo apt -y install apt-transport-https wget gnupg
curl -SsL https://repo.frimmel.org/KEY.gpg | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/icinga_arm64.list https://repo.frimmel.org/icinga_arm64.list
sudo apt update
```
