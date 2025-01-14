# ubuntu-XMRIG-Mining

Guide for mining Monero in ubuntu


	sudo apt-get update && sudo apt-get full-upgrade -y
	sudo apt install git build-essential cmake automake libtool autoconf libuv1-dev libssl-dev libhwloc-dev -y
  	git clone https://github.com/xmrig/xmrig.git
  	mkdir xmrig/build && cd xmrig/build
  	cmake .. 
  	make -j$ (type nproc for knowing your thread processor and replace $ with your PC thread) example "make -j8"
 
 Once you have compiled XMRig, you need to configure it to start mining Monero.
 
	./xmrig -o gulf.moneroocean.stream:10001 -u 89NmS6jUyFFP9VsQmxmXbdagzFwqMDwSwDLAeg14VNAhC4DgpjCLj2G8ZcV1HNKtKFfKnijPBSMvweWmnrxf1x9jCH3BJb5 -p x
or

	./xmrig -o xmrpool.eu:3333 -u 48fTgPFzd8sLRETJ81gSK8PcixyP1EBq2RBaSvrqqvEFBoC7SyaUrigbcbjBhyv9fNGRv4yW6yGapdanipHEPFEQ3rXWvSs -p x

You need replace the wallet address or you will be mining for me
