Simple GUI interface mockup to demonstrate Subatomic swaps (based on dexp2p) Komodo technology.

Dependencies:
```
python 3.7+ is needed (because of this bug https://stackoverflow.com/questions/52440314/ttk-spinbox-missing-in-tkinter-ttk/52440947)
sudo apt-get install python3-pip libgnutls28-dev python3-tk
pip3 install setuptools wheel slick-bitcoinrpc
```
For subatomic bin proper work, from `~/folderwithlatestjl777daemon/src` folder:
```
gcc -o subatomic cc/dapps/subatomic.c -lm
ln ~/folderwithlatestjl777daemon/src/cc/dapps/subatomic.json $HOME/komodo/src/subatomic.json
sudo ln -sf ~/folderwithlatestjl777daemon/komodo/src/komodo-cli /usr/local/bin/komodo-cli
```

To run:
`cp -r * ~/folderwithlatestjl777daemon/src`
`python3 main.py`

![screenshot](https://i.imgur.com/HeXUFEU.png)
