
EtherNode is a PoS-based cryptocurrency.

EtherNode uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01p,
			  Berkeley DB 4.8,
			  QT5 to compile


Block Spacing: 60 Seconds
Stake Minimum Age: 24 Hours

Port: 28880
RPC Port: 28881


BUILD LINUX
-----------
1) git clone https://github.com/ethernode/EtherNode

2) cd EtherNode/src

3) sudo make -f makefile.unix            # Headless

(optional)

4) strip ethernoded

5) sudo cp ethernoded /usr/local/bin
