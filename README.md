# shadowsocksR-libev

## Compiling from source (Ubuntu 18.04 LTS used)
```
sudo apt-get install git build-essential cmake aptitude zlib1g-dev -y
sudo aptitude install build-essential -y
sudo apt-get install libsodium-dev libpcre3 libpcre3-dev libssl-dev -y
git clone https://github.com/jitdor/shadowsocksr-libev.git
cd shadowsocksr-libev
sudo ./configure --prefix=/usr/local/shadowsocksR --disable-documentation
sudo make -j6
sudo make install
```

The executables (ss-local, ss-nat, ss-redir) will be placed in /usr/local/shadowsocksR/bin/
