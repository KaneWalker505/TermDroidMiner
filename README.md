# TermDroidMiner


Android termux (terminal) sha256d crypto miner
SOLO MINER

THIS MINER DOES NOT send shares of lower difficulty it attempts to solve and mine the entire block ONLY



**INFO**


CPU sha256 Crypto miner for ARMV8 Android.

(Average Hashrate | 150khz/sec Hash Rate)

tested and working on the following mining node pool servers

solo.ckpool.org | 
zpool.ca


**NOTE**


This is a *SOLO MINER*

IT WILL **NOT** attempt to send shares of lower difficulty it will ignore
share jobs and share accepts completely


THIS miner is coded to ONLY work as a SOLO MINER
it was coded with mobile in mind, it saves on network data and bandwith by not mining shares but attempting to solve and mine the block only itself. This means it will use VERY little networking/internet data.


The Miner works like so:

After Server / Wallet input the miner will attempt to find a block hash that meets the difficulty target by adjusting the nonce value and repeatedly hashing the block header. Once a valid hash meets target requirment of network block. Result
is sent to mining node server. When server accepts your block solving hash you earn full rewards of solving the block.

THIS MINER DOES NOT send shares of lower difficulty it attempts to solve and mine the entire block ONLY

**Example Command**


./TAM -h   (List help command example) 


./TAM ServerAddress Port Wallet Password

You can run without arguments aswell
if you run the program without arguments, the default zpool server will be used on port 3333
the miner will ask for input of your wallet and password then after.



**mining stratum difficulty**

You wont need to worry about mining stratum difficulty

Can 100% ingore mining stratum difficulty when using this miner


Sense it attempts to ONLY solo mine the block hash itself

mining stratum difficulty is only used when mining shares of the block.

Sense this miner does not attempt to hash or mine shares this can be ignored

So stratum difficulty is just set by pools and reflects the kinds of hardware and software used and how many miners there are, and is low enough so that all miners with adequate hashpower can share in blocks found

It has nothing to do with the actual BLOCK hash difficulty of the crypto block itself when solo mining


