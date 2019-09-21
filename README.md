# MN-Setup Guide (with 2 ip on VPS for 2 masternodes)

wget -q https://github.com/coinmarketrun/MN_Script/blob/master/for2ip_mobinode.sh

sudo chmod +x for2ip_mobinode.sh

./for2ip_mobinode.sh

When prompted to Enter your mobinode Masternode GEN Key.

Paster your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain.
For check enter below command.

mobinode1-cli getinfo

When Node Fully Synced enter below command for check masternode status.

mobinode1-cli masternode status
