## Mycroft Desktop Repo
Completely unofficial debian repo for Mycroft related APT packages, packages has mainly been tested with Ubuntu 18.04.

### Add the repo
To add the repo to your list of repos enter the following in a terminal:

```
curl https://forslund.github.io/mycroft-desktop-repo/mycroft-desktop.gpg.key | sudo apt-key add - 2> /dev/null && echo "deb http://forslund.github.io/mycroft-desktop-repo bionic main" | sudo tee /etc/apt/sources.list.d/mycroft-desktop.list
apt-get update
```

Afterwards you should for example be able to run

```
apt-get install mimic
```

to install mimic.
