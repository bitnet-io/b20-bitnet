



# B20 

# be warned you can build all of the source code but there is no front-end available because the actual needed front-end is not open source

# all of the dependencies are here https://github.com/orgs/alexgo-io/repositories


The first version of B20, an order matching protocol for peer to peer exchange of digital assets written in Clarity.

The protocol only facilitates order matching, which means that the actual order generation and order books are managed off-chain. Users will first deploy a wallet contract and deposit their digital assets into it. They then sign order structs in order to trade.

![b20 v1 diagram](assets/b20.png)
