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

After Server / Wallet input the miner will attempy to find a block hash that meets the difficulty target by adjusting the nonce value and repeatedly hashing the block header. Once a valid hash meets target requirment of network block. Result
is sent to mining node server.

THIS MINER DOES NOT send shares of lower difficulty it attempts to solve and mine the entire block ONLY

**Example Command**
./TAM -h   (List help command example) 


./TAM ServerAddress Port Wallet Password

You can run without arguments aswell
if you run the program without arguments, the default zpool server will be used on port 3333
the miner will ask for input of your wallet and password then after.
