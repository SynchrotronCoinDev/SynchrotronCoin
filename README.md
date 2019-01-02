**Solo Mining Guide**

1. Run the wallet or build the deamon, if you need help look at /doc.

2. Edit your synchrotroncoin.conf, its located near by your wallet.dat, if it is not in (.)SynchrotronCoinV2 directory, you have to create this         file by yourself.

add the following lines to your .conf file:

        rpcuser=yourusername   
        rpcpassword=yourpassword 
        server=1

3. Download CPU Miner, for Windows you can use for example this one : https://github.com/tpruvot/cpuminer-multi/releases/download/v1.3.1-multi/cpuminer-multi-rel1.3.1-x64.zip

4. Edit your .bat file to this:
        cpuminer-gw64-corei7 -a scrypt -o http://127.0.0.1:22222/ -u yourusername -p yourpassword
        pause
5. Run the .bat file and you should start mining. Dont forget that your wallet has to run all the time you want to mine.




