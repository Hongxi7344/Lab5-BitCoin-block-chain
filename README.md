In this lab we are going to get an old block from the BitCoin block chain and demonstrate how any changes would be caught by the BitCoin network.

Requirements:

Connect to a peer in the P2P BitCoin network and get the block number that corresponds to your SU ID number (your number modulo 10,000).
Display the transactions in the block. 
Have your program manipulate one of the transactions in the block to change its output account, then fix up the block to correctly represent this modified data (fix the merkle-tree hashes, etc.). 
Then show with a program-generated report how the hash of the block has changed and the ways in which this block would be rejected by peers in the network. 
Program written in Python 3 with no use of publicly available BitCoin libraries (except makeseeds as shown below).
Use TCP/IP to communicate with a full node in the network.
