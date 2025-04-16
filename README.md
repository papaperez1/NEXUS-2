# NEXUS Testnet Phase 3....
## UBUNTU 22.04 or later//.
```
sudo su -
apt update
sudo apt install build-essential
```
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
echo 'source $HOME/.cargo/env' >> ~/.bashrc
```
```
source ~/.bashrc
```
```
sudo apt install libssl-dev
export PKG_CONFIG_PATH=/usr/lib/pkgconfig
```
```
apt install pkg-config
```
```
curl -OL https://github.com/protocolbuffers/protobuf/releases/download/v25.1/protoc-25.1-linux-x86_64.zip && \\
    unzip -o protoc-25.1-linux-x86_64.zip -d /usr/local bin/protoc && \\
    unzip -o protoc-25.1-linux-x86_64.zip -d /usr/local 'include/*' && \\
    rm -f protoc-25.1-linux-x86_64.zip
```
```
curl https://cli.nexus.xyz/ | sh
```

If you have less than 8 GB RAM run thiss
```
sudo fallocate -l 10G /swapfile && sudo chmod 600 /swapfile && sudo mkswap /swapfile && sudo swapon /swapfile && echo '/swapfile none swap sw 0 0' | sudo tee -a /etc/fstab && sudo sysctl vm.swappiness=100 && echo 'vm.swappiness=100' | sudo tee -a /etc/sysctl.conf
```
