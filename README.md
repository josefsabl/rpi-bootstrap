# rpi-bootstrap

## Init script

```
sudo apt update
sudo apt upgrade
sudo apt install \
  mc \
  php \
  nginx \
  mongodb \
  composer \
  nodejs \
  && echo "Dependencies installed."

sudo apt autoremove
echo "Done."
```
