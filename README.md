
**Install on GNU/Linux - Ubuntu**

<code>sudo apt update && sudo apt upgrade -y && sudo apt install build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev git libssl1.0.0-dbg libdb-dev libdb++-dev libboost-all-dev libminiupnpc-dev libminiupnpc-dev libevent-dev libcrypto++-dev libgmp3-dev -y

git clone https://github.com/eduardoalthaus/inoscoin.git && cd inoscoin && mkdir -p src/obj/zerocoin && chmod +x src/leveldb/build_detect_platform && cd src/leveldb && make libleveldb.a libmemenv.a && cd .. && make -f makefile.unix USE_UPNP=-</code>



