# Supply chain & data auditing

This project containts an Ethereum DApp that demonstrates a stock between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running will look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)

### Prerequisites

To run we need installed ganache-cli, Truffle and enabled MetaMask extension in your browser

### Running project 


npm install

Launch Ganache:


ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"


Our terminal should look like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```


![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp

```
npm run dev
```

## Built With

* Ethereum- Ethereum is a decentralized platform that runs smart contracts
* IPFS(https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.
* node - All the backend the the APi's have been coded in the base of node.

## Acknowledgments

* Node
* Solidity
* Ganache-cli
* Truffle
* IPFS
