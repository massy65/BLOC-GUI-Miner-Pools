# Turtlecoin pool for GUI Miner

This repository will contain a list with the Monero, Turtlecoin and Haven pools. This is used in the [BLOC GUI Miner](https://github.com/furiousteam/BLOC-GUI-Miner), the official [bloc.money](https://bloc.money/) miner, which can also be used to mine these coin.  
For now, only forknote pool scripts are supported.

## How to add / edit a pool

Edit the json file coresponding to the coin you want to add a pool for.

You need to add the followings keys for each pool you add:

* name - the name of the pool
* url - the url of the pool
* apiAddress - the api address (URL) from where the stats will be retrieved
* scriptType - 2 values can be used here: forknote (recommended) or custom
* miningAddress - the address of the pool used by the miner
* miningPort - the port of the pool used by the miner