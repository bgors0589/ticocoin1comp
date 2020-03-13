Copyright (c) 2009-2020 Bitcoin Developers
Copyright (c) 2011-2020 Ticocoin Developers

Que es Ticocoin?
-----------------------

Ticocoin es una criptomoneda que utiliza scrypt como algoritmo de trabajo similar a Bitcoin y Litecion.
 - Block targets (Consigue el bloque) ~ de 5 minutos
 - Halvin a los 50k Bloques (reduccion de recompenza a la mitad)
 - ~ 4 millones de monedas en total


Ticocoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 5 minute block targets
 - subsidy halves in 50k blocks
 - ~4 million total coins

Recompensa Mineros.
  - 40 Coins (Monedas)	


License - Licencia
----------------------------

Ticocoin se lanza bajo los términos de la licencia MIT. Vea `COPYING` para más
información o consulte http://opensource.org/licenses/MIT.

Ticocoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.






Repositorios a tener en Ubuntu para la compilacion
----------------------------------------------------------


sudo apt-get install git
 
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils
 
sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev
 
sudo apt-get install libboost-all-dev
 
sudo apt-get install software-properties-common
 
sudo add-apt-repository ppa:bitcoin/bitcoin
 
sudo apt-get update
 
sudo apt-get install libdb4.8-dev libdb4.8++-dev
 
sudo apt-get install libminiupnpc-dev
 
sudo apt-get install libzmq3-dev
 
sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler
 
sudo apt-get install libqt4-dev libprotobuf-dev protobuf-compiler
 
git clone -b 0.8 https://github.com/litecoin-project/litecoin.git
