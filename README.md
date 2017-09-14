<p>
ALGO:XEVAN
Dark Gravity wave retarget
250k Collateral
Final POW block  100000
POW blocks every 5 minutes
instant-tx
Darksend
Obfuscation:coinjoin
rpc: 72013 p2p: 25070
Premine for swap 30000000 
- 10% Pos reward roughly every 40k blocks
+ %90 to pos and MN
---------------------------------------------------------------------------------------------------------------------

sk21 Windows wallet with 250000k 

Go to Tools -> Debug console and enter the command "masternode genkey".

In Debug Console enter the command "getaccountaddress MyMasternode".

send exactly 250000 to the address generated

Enter "masternode outputs" and copy the output

Edit masternode.conf 

It should look something like this
<masternode> <yourip:25070> <PRIVATEKEY> <Proof of transaction>

rpcuser=
rpcpassword=
rpcallowip=127.0.0.1
listen=0
server=1
daemon=1
logtimestamps=1
maxconnections=256
masternode=1
externalip=your public ip address:25070
bind=your public ip address:25070
masternodeaddr=your public ip address:25070
masternodeprivkey= Masternode private key output 

Restart your wallet
Activate your MN in Masternode tab 
Your wallet must be unlocked for MN to earn
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++</p>
each Masternode is secured with collateral of 250K Sk21</p>
<p>rpc: 72013 p2p: 25070 </p>
