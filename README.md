
**Install on GNU/Linux - Ubuntu**

<code>sudo apt update && sudo apt upgrade -y && sudo apt install build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev git libssl1.0.0-dbg libdb-dev libdb++-dev libboost-all-dev libminiupnpc-dev libminiupnpc-dev libevent-dev libcrypto++-dev libgmp3-dev -y

mkdir Inoscoin && cd Inoscoin && wget https://github.com/tnjtnj/tnj/archive/rebranding.tar.gz && tar -xzvf rebranding.tar.gz && cd src && make -f makefile.unix RELEASE=1</code>
