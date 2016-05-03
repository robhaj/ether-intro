#[Ethereum?](https://www.ethereum.org/)
The Ethereum network
- is a public blockchain platform  
- has a programmable transaction functionality

It extends bitcoin's blockchain adding "smart contracts". These are small programs added to the blockchain.

Ethereum operates as a large distrbuted computer, executing programs on nodes all over the world.

## BlockChain?
Think of the blockchain as a distributed database containing a growing list of transaction records  hardened against tampering.

## Smart contracts
Computer protocols that verify or enforce the negotiation or performance of a contract, or that make a contractual clause unnecessary.

Can be implemented in various languages, compiled into bytecode for the Ethereum Virtual Machine (EVM) before being deployed to the blockchain.

## Ether
*"THE CRYPTO-FUEL FOR THE ETHEREUM NETWORK"*

- Allows developers to create markets, store registries of debts or promises, move funds in accordance with instructions given long in the past, like futures contracts or a will, all without a middle man.
- Form of payment made by the clients of the platform to the machines executing the requested operations.
- The incentive ensuring that developers write quality applications (wasteful code costs more), and that the network remains healthy (people are compensated for their contributed resources).

The total supply and its rate of issuance was decided by the donations gathered on the 2014 presale.

- 60 million ether created to contributors of the presale.

- 12 Million (20% of the above) were created to the development fund, most of it going to early contributors and developers and the remaining to the Ethereum Foundation

- 5 ethers are created every block (about every 15-17 seconds) to the miner of that block

- Issuance of ether is capped at 18 million ether per year (this number equals 25% of the initial supply).

So while issuance is fixed, relative inflation is decreased every year. If this issuance was kept indefinitely, at some point the rate of new tokens every year would reach the average amount lost yearly (by misuse, accidental key lost, death of holders etc) and there would reach an equilibrium. However, sometime in 2017, Ethereum will be switched to a new consensus algorithm under development, called Casper that is expected to be more efficient and require less mining subsidy.

### Who needs ether?
Developers who intend to build apps that will use the ethereum blockchain. Users who want to access and interact with smart contracts on the ethereum blockchain.


## Decentralized Apps (DApp)
- Applications that run exactly as programmed without any possibility of downtime, censorship, fraud or third party interference.
- Some industries currently implementing DAPP's are finance, IoT, identity management, farm-to-table produce, electricity sourcing/pricing, and sports betting.
- On traditional server architectures, every application has to set up its own servers that run their own code in isolated silos, making sharing of data hard. If a single app is compromised or goes offline, many users and other apps are affected. On a blockchain, anyone can set up a node that replicates the necessary data for all nodes to reach an agreement and be compensated by users and app developers. This allows user data to remain private and apps to be decentralized like the Internet was supposed to work.

##[Embark](http://iurimatias.github.io/embark-framework/)

Take a look at my Embark primer available here:
[EMBARK-PRIMER](https://github.com/robhaj/embark-primer)

Embark is a framework that allows you to easily develop and deploy DApps.

You can:

- Automatically deploy contracts and make them available in your JS code. Embark watches for changes, and if you update a contract, Embark will automatically redeploy the contracts (if needed) and the dapp.
- Do Test Driven Development with Contracts using Javascript.
- Easily deploy to & use decentralized systems such as IPFS (InterPlanetary File System, a new hypermedia distribution protocol)
- Keep track of deployed contracts, deploy only when truly needed.
- Quickly create advanced DApps using multiple contracts.
