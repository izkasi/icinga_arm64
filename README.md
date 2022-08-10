# icinga_arm64

Unofficial repository for icinga2 packages for Debian Bullseye on arm64 platform.
Don't use it in production!

It's still early, but the most setups should be possible by now.

At the moment the latest stable of following packages are being built:
* icinga2_XXX.bullseye_arm64.deb
* icinga2-bin_XXX.bullseye_arm64.deb
* icinga2-common_XXX.bullseye_all.deb
* icinga2-dbg_XXX.bullseye_arm64.deb
* icinga2-doc_XXX.bullseye_all.deb
* icinga2-ido-mysql_XXX.bullseye_arm64.deb
* icinga2-ido-pgsql_XXX.bullseye_arm64.deb
* icingacli_XXX.bullseye_all.deb
* icingadb_XXX.bullseye_arm64.deb
* icingadb-redis_XXX.bullseye_all.deb
* icingadb-redis-sentinel_XXX.bullseye_arm64.deb
* icingadb-redis-server_XXX.bullseye_arm64.deb
* icingadb-redis-tools_XXX.bullseye_arm64.deb
* icingadb-redis-tools-dbgsym_XXX.bullseye_arm64.deb
* icingadb-web_XXX.bullseye_all.deb
* icinga-php-common_XXX.bullseye_arm64.deb
* icinga-php-library_XXX.bullseye_arm64.deb
* icinga-php-thirdparty_XXX.bullseye_arm64.deb
* icingaweb2_XXX.bullseye_all.deb
* icingaweb2-common_XXX.bullseye_all.deb
* icingaweb2-module-doc_XXX.bullseye_all.deb
* icingaweb2-module-monitoring_XXX.bullseye_all.deb
* php-icinga_XXX.bullseye_all.deb
* vim-icinga2_XXX.bullseye_all.deb

## Use the repository
```bash
sudo apt update
sudo apt -y install apt-transport-https wget gnupg curl
curl -SsL https://repo.frimmel.org/KEY.gpg | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/icinga_arm64.list https://repo.frimmel.org/icinga_arm64.list
sudo apt update
```

