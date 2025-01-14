# ubuntu-XMRIG-Mining

Guide for mining Monero in ubuntu


	sudo apt-get update && sudo apt-get upgrade
	sudo apt install git build-essential cmake automake libtool autoconf libuv1-dev libssl-dev libhwloc-dev
  	git clone https://github.com/xmrig/xmrig.git
  	cd xmrig
  	mkdir xmrig/build && cd xmrig/build
  	./build_deps.sh && cd ../build
  	cmake .. -DXMRIG_DEPS=scripts/deps
  	make -j$ (type nproc for knowing your thread processor)
 
 Once you have compiled XMRig, you need to configure it to start mining Monero.
 
	./xmrig -o gulf.moneroocean.stream:10001 -u 89NmS6jUyFFP9VsQmxmXbdagzFwqMDwSwDLAeg14VNAhC4DgpjCLj2G8ZcV1HNKtKFfKnijPBSMvweWmnrxf1x9jCH3BJb5 -p x
or

	./xmrig -o xmrpool.eu:3333 -u 48fTgPFzd8sLRETJ81gSK8PcixyP1EBq2RBaSvrqqvEFBoC7SyaUrigbcbjBhyv9fNGRv4yW6yGapdanipHEPFEQ3rXWvSs -p x
