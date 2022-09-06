# Vanilla OS PPA

## Setup
```bash
curl -s --compressed "https://vanilla-os.github.io/ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/file.list "https://vanilla-os.github.io/ppa/file.list"
sudo apt update
```
