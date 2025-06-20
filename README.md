# Cysic Node
Running Verifer and Prover Node Cysic

Register : https://cysic.xyz/zk
Submit Code : 
Start run Prover/Verifier Node
Completed Task
Stake CGTS

1. RUN VERIFER NODE : 
Download Pack

```
curl -L https://github.com/cysic-labs/cysic-phase3/releases/download/v1.0.0/setup_linux.sh > ~/setup_linux.sh && bash ~/setup_linux.sh 0x-Fill-in-your-reward-address-here
```
"0x-Fill-in-your-reward-address-here"Change with your adress

Start Verifer Program

```
cd ~/cysic-verifier/ && bash start.sh
```

2. RUN PROVER NODE
Download Package

```
curl -L https://github.com/cysic-labs/cysic-phase3/releases/download/v1.0.0/setup_prover.sh > ~/setup_prover.sh && bash ~/setup_prover.sh 0x-Fill-in-your-reward-address-here Your_RPC_URL
```

* "0x-Fill-in-your-reward-address-here" Change with your adress
* "Your_RPC_URL" Change with RPC from Alchemy

Start Prover Node

```
cd ~/cysic-prover/ && bash start.sh
```
* Docs : https://docs.cysic.xyz/tutorial-docs/how-to-run-a-prover-node
* Source : https://x.com/cysic_xyz/status/1930264646079971458
