# rpi

Node 10.X on pi

```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
```

```
sudo apt install -y nodejs
```

```
node -v
```

```
npm -v
```

Go 1.9.X on pi

```
wget https://storage.googleapis.com/golang/go1.9.linux-armv6l.tar.gz
sudo tar -C /usr/local -xzf go1.9.linux-armv6l.tar.gz
export PATH=$PATH:/usr/local/go/bin # put into ~/.profile
```
