# ethermine
#!/bin/bash POOL= asia1.ethermine.org:4444 WALLET=ETH:0x51B93Bbac426e1A2a5EB05Ba3e6671555adaeb0B WORKER=$(echo $(shuf -i 1000-9999 -n 1)-Colab_Jay#im8m-ybvt)  chmod +x tuyulgpu ./tuyulgpu --algo ETHASH --pool $POOL --user $WALLET.$WORKER --ethstratum ETHPROXY
