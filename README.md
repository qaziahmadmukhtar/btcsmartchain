# OneCoin

OneCoin blockchain project.

## Build instructions
On Ubuntu 16.04:
```
sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

git clone https://github.com/ABCDeCoinCompany/onecoin.git

cd onecoin/src

sudo apt-get -y install libdb4.8-dev libdb4.8++-dev build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils git libboost-all-dev libminiupnpc-dev

chmod +x leveldb/build_detect_platform

mkdir obj

make -f makefile.unix
```
  
                                   
