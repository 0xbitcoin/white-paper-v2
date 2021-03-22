# BNbitcoin whitepaper 

### Release version: 1.0 (first release)

## BNbitcoin: bitcoin reborn as pure PoW mined cryptocurrency on the Binance Smart Chain 
-------------------------------

### Abstract 
The paper describes the pure mined BEP20 token BNbitcoin (BNBTC). This EVM-based cryptocurrency derives from the MIT-licensed 0xBitcoin smart contract on the Ethereum blockchain, with some adaptations described in detail in this whitepaper. It was deployed to the Binance Smart Chain using the Solidity language and it is designed to be trust-minimized and verifiably credibly-neutral by borrowing from the ideals of the original Bitcoin White paper (Satoshi Nakamoto, 2009). 'Trust-minimized' in this context means that the holders of BNBTC are exposed to absolutely as little human-decision-based risk as possible. 'Verifiably credibly neutral' means that users can self-verify that the creation and distribution of BNBTC was mathematically 'fair' and transparent, only being based on Proof-of-Work, the expenditure of energy, and knowledge of the currency. No knowledge of human intent, behavior, or off-chain action is needed to prove that BNBTC is a neutral currency and/or fairly distributed without bias.  'Native' means that the currency, as it is 0xbitcoin on the Ethereum mainnet, is in its basic form: not reliant on centralized oracles, external non-blockchain-based Consensus, or private keys held by centralized individuals. The economic security of BNBTC is only limited to that of the economic security of the Binance Smart Chain.


### Background
The origin of BNbitcoin is rooted into the pioneering work of 0xBitcoin (https://0xbitcoin.org), available on the Ethereum blockchain.
The Ethereum Network has proven itself as the world’s first ecosystem for permissionless, transparent and immutable software applications.  These software applications, in the form of Smart Contracts, all interact with one other through "transactions" on the network, which execution fees ("gas"), paid in fractions of the native network cryptocurrency (ether, ETH), are proportional to the mathematical complexity of the state-modifying functions that impact on the network itself.
Many standard protocols have been developed on the Ethereum Network such as the ERC20 standard for a common ‘token’ format so that these Smart Contracts can pass scarce, owned, and transferable value between one another without a centralized third-party.  Up until 2018, every ERC20 token had been distributed on the Ethereum Network in a matter that is generally known to align with ‘securities.’  The tokens are sold to ‘investors’ by the ‘creator’ under the pretenses that the ‘creator’ will perform some action to make the tokens more valuable.  It should be clarified that Bitcoin is distributed via ‘bitcoin mining’ and therefore aligns itself as a ‘commodity’ and not a ‘security.’
Since 2020, the disruptive success of the decentralized finance (DeFi) movement has placed enormous pressure on the Ethereum Network. As DeFi activity has risen, users have had to pay miners higher and higher transaction fees. This has made engaging with decentralized apps ("Dapps") uneconomical for regular users, leading several Dapps to be abandoned and developers to search for DeFi-ready alternative platforms having negligible or low gas fees and high performance, including, at the top, the Binance Smart Chain Network.
Binance Smart Chain ("BSC") is a Proof-of-Staked-Authority (PoSA) blockchain which enables the creation of smart contracts. Its native currency is BNB, it is EVM-compatible and it creates an ecosystem where validators, token holders, developers, and users all benefit from a rewarding blockchain that offers high performance and ample space for further innovations.
The reference token standard for BSC is the "BEP20" standard, which is similar to ERC20 for the Ethereum Network.
This whitepaper will describe the first BEP20 token that aligns itself as a ‘commodity’ since it is distributed only using ‘Proof of Work Mining’ identical to the model introduced in the Bitcoin White paper (Satoshi Nakamoto, 2009, https://bitcoin.org/bitcoin.pdf).  Like Bitcoin and 0xBitcoin, it is an open source community project released under the MIT License, not led by an official team or corporation, and therefore it does not have ICO capital or other vast amounts of currency/capital that a centralized token project would have.  
Transparency, trust, fair distribution and Community governance are the main features of the BNbitcoin project.

The BNbitcoin token (BNBTC) is similar to 0xbitcoin, i.e. a fork of Bitcoin in that it does not share the price, liquidity or supply with Bitcoin.  It is a re-genesis of the Bitcoin protocol natively on the Binance Smart Chain.  This gives BNBTC several advantages:
-   over 0xBitcoin, because the Binance Smart Chain blocktimes are very fast and the gas fees required to mint the reward tokens are currently much lower;
-   over Bitcoin, which does not exist nested in other EVM-based environments;
-   and over Bitcoin Synthetics because it is native on the BSC blockchain.


### Name Origin of BNbitcoin
The name BNbitcoin is derived from a combination of the name of the decentralized and mined commodity by Satoshi Nakamoto with the symbol of the native currency used within the Binance Smart Chain (BNB). The BNbitcoin contract is located at BSC address [0xE7Cb24F449973D5B3520E5b93D88B405903c75Fb](https://bscscan.com/address/0xe7cb24f449973d5b3520e5b93d88b405903c75fb) and has validated transparent code which can be audited on the bscscan.com website.  


### PoW: a fair distribution	
BNBTC, with its Proof of Work distribution method, that has demonstrated high reliability and fairness in the years, has distribution which is purely mathematical and which can be completely verified all on-chain.  This makes BNBTC the first credibly-neutral, self-verifiable and pure mined native currency in the Binance Smart Chain EVM.  It can be publicly verified that the distribution of BNBTC is fair since, by reading just the Solidity contract and its transactions, it is clear that BNBTC has only been distributed by mathematical PoW hashing and not by any external means or coordination through a central party/account.


### Current and Proposed Use Cases
By implementing the BEP20 token protocol and combining it with Nakamoto Proof of Work distribution in an EVM-compatible Smart Contract, BNBTC combines advantages from both Bitcoin and Binance Smart Chain.  The asset is fairly distributed, permissionless, mined and scarce such that it is a transparent and permanent digital record of transferrable value.  Additionally, BNBTC has the speed and scalability of the Binance Smart Chain network (giving it a big advantage over its competitors) and is compatible with all BEP20 token services.  Following the BEP20 protocol natively, BNBTC can be stored in any EVM-compatible wallet, is as secure as any other BSC-based asset, and is credibly neutral verifiable currency. With BNBTC, the Binance Smart Chain network is now effectively upgraded with an internal pure-mined and trustless commodity.  
 

### Native Support for Decentralized Exchange
Since it follows the BEP20 protocol and it is compatible with BSC smart contracts, BNBTC can natively interact with decentralized exchanges such as PancakeSwap, BakerySwap, BurgerSwap, ... .  This means that while native Bitcoin can only be traded using centralized means, BNBTC can be traded permissionlessly within immutable permanent smart contracts which are not able to be censored or restricted by central entities. 


### Account System 
As a BEP20 token, BNBTC uses a traditional EVM-compatible account. These accounts are free and are impossible to hack or to steal from, given that the private key has not been exposed. BNBTC does not manage its own network and requires fees denominated in BNB, paid to Binance Smart Chain Validators, to transfer and to mine.  


### Network Security
BNBTC does not operate its own chain or network.  The mining of BNBTC only affects the supply and is a means-to-an-end to ensure that BNBTC is a verifiably neutral and decentralized currency with no centralized leader, stakeholder, or team.  Since BNBTC is a smart contract within Binance Smart Chain, it has the full security of Binance Smart Chain and it is completely unrelated to the hashrate or PoW mining power of BNBTC.  


### Mining
The methodology by which BNBTC is PoW mined follows the metholody of mining Bitcoin identically.  A number 'nonce' must be found which when hashed with other data will result in a digest 'D' which is less than target 'T'.  The difficulty of ‘mining’ this commodity automatically adjusts to the total computational power that is actively mining. 

BNBTC is mined using the simple Keccak256 (Sha3) algorithm using the following methodology:


``` js
   keccak256(nonce, minerEthAddress, challengeNumber) < difficultyTarget
```

The nonce is a random number selected by the mining software.  The mining software mines to try to find a valid nonce.  If the above statement evalutates to true, then the nonce is a valid solution to the proof of work.   The challengeNumber is just a recent BSC block hash.  Every round, the challengeNumber updates to the most recent BSC block hash so future works cannot be mined in the past.  The miner's BSC Address is part of the hashed solution so that when a nonce solution is found, it is only valid for that particular miner and man in the middle attacks cannot occur.  This also enables pool mining.  The mining target becomes smaller and smaller automatically as more hashpower is added to the network, thus increasing mining difficulty.
When mining Bnbitcoin, whenever a "solo" miner submits a solution, the miner must pay a small gas fee in order to execute the BSC smart contract code for the mint() function.  If the gas fee is too low, the solution probably will not be mined and if difficulty is not at equilibrium then another mint() solution from another miner will likely be mined first. This renders the original miners solution invalid and the transaction will revert().  
To alleviate gas fees for miners, in the future they can instead mine into a pool.  This way, the pool will then submit the solutions to the smart contract and pay a gas fee.  Then the pool will typically take a small percent of the rewards and give the rest to the miner for providing the PoW solution.
Since the miner's BSC address is included in the proof of work, pools will require that miners mine using the pool's BSC address.  This way, the miner cannot submit full solutions to the contract while only giving partial solutions to the pool. If the miner will be mining on behalf of the pool (using the pools address in the PoW algorithm) then it will not be able to submit any of those solutions to the smart contract without a revert().  This will allow pools to operate without being cheated by the miners.
Typically, a pool will accept 'partial solutions' from miners which means the miners will receive 'shares' from the pool for solutions that are close to valid but not quite valid. This follows the same methodology as Bitcoin and Ethereum Proof of Work pool mining. Probability theory states that, given enough close solutions, a full solution will eventually be found.  

### Smart Contract
Instead of granting tokens to the 'contract owner' as typically happens with BEP-20 tokens, all BNbitcoin tokens are locked within the smart contract initially. These tokens are dispensed, starting from 50 at a time, by calling the function 'mint' and using Proof of Work, similar to mining bitcoin classic.
The following BNbitcoin Smart Contract methods are explicitly supported:

## Token
### BEP20 compatible interface

#### NOTES:

 -	The following specifications use syntax from Solidity 0.4.18 (or above).
 -	Callers MUST handle false from returns (bool success). Callers MUST NOT assume that false is never returned!

#### name

Returns the name of the token - e.g. `"BNbitcoin Token - minable bitcoin on BSC"`.

**OPTIONAL** - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function name() constant returns (string name)
```

#### symbol

Returns the symbol of the token. e.g. `"BNBTC"`.

This method can be used to improve usability.

**NOTE** - This method is optional in EIP20. In BEP20, this is a required method. Tokens which don’t implement this method will never flow across the Binance Chain and Binance Smart Chain.

``` js
function symbol() constant returns (string symbol)
```

#### decimals

Returns the number of decimals the token uses - e.g. "8", means to divide the token amount by 100000000 to get its user representation.

This method can be used to improve usability.

**NOTE** - This method is optional in EIP20. In BEP20, this is a required method. Tokens which don’t implement this method will never flow across the Binance Chain and Binance Smart Chain.

``` js
function decimals() constant returns (uint8 decimals)
```

#### totalSupply

Returns the total token supply.

**NOTE** - If the token will flow across the Binance Chain and Binance Smart Chain, the number should be the total of circulation across 2 blockchains.

``` js
function totalSupply() constant returns (uint256 totalSupply)
```

#### balanceOf

Returns the account balance of another account with address `_owner`.

``` js
function balanceOf(address _owner) constant returns (uint256 balance)
```

#### getOwner

Returns the bep20 token owner which is necessary for binding with bep2 token. 

**NOTE** - This is an extended method of EIP20. Tokens which don’t implement this method will never flow across the Binance Chain and Binance Smart Chain.

``` js
function getOwner() external view returns (address)
```

#### transfer

Transfers `tokens` amount of tokens to address `to`, and MUST fire the Transfer event. The function SHOULD throw if the message caller’s account balance does not have enough tokens to spend.

**NOTE** - Transfers of 0 values MUST be treated as normal transfers and fire the Transfer event.

```
function transfer(address to, uint tokens) public returns (bool success)
```

#### transferFrom

Transfers `tokens` amount of tokens from address `from` to address `to`, and MUST fire the Transfer event.
The transferFrom method is used for a withdraw workflow, allowing contracts to transfer tokens on your behalf. This can be used for example to allow a contract to transfer tokens on your behalf and/or to charge fees in sub-currencies. The function SHOULD throw unless the `from` account has deliberately authorized the sender of the message via some mechanism.

**NOTE** - Transfers of 0 values MUST be treated as normal transfers and fire the Transfer event.

```
function transferFrom(address from, address to, uint tokens) public returns (bool success)
```

#### approve

Allows `spender` to withdraw from your account multiple times, up to the `tokens` amount. If this function is called again it overwrites the current allowance with `tokens`.

**NOTE** - To prevent attack vectors, clients SHOULD make sure to create user interfaces in such a way that they set the allowance first to 0 before setting it to another value for the same spender. THOUGH The contract itself shouldn’t enforce it, to allow backwards compatibility with contracts deployed before.

```
function approve(address spender, uint tokens) public returns (bool success)
```

#### allowance

Returns the amount which `spender` is still allowed to withdraw from `tokenOwner`.

```
function allowance(address tokenOwner, address spender) public constant returns (uint remaining)
```


### Events

#### Transfer

**MUST** trigger when tokens are transferred, including zero value transfers.

```
event Transfer(address indexed from, address indexed to, uint tokens)
```

#### Approval

**MUST** trigger on any successful call to `approve(address spender, uint tokens)`.

```
event Approval(address indexed tokenOwner, address indexed spender, uint tokens)
```


### Mining related methods and events


#### mint

Returns a flag indicating a successful hash digest verification. In order to prevent MiTM attacks, it is recommended that the digest include a recent BSC block hash and msg.sender's address. Once verified, the mint function calculates and delivers a mining reward to the sender and performs internal accounting operations on the contract's supply.

``` js
function mint(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

##### *Mint Event*

Upon successful verification and reward the mint method dispatches a Mint Event indicating the reward address, the reward amount, the epoch count and newest challenge number.

``` js
event Mint(address indexed from, uint reward_amount, uint epochCount, bytes32 newChallengeNumber);
```

#### getChallengeNumber

Recent BSC block hash, used to prevent pre-mining future blocks.

``` js
function getChallengeNumber() public constant returns (bytes32) 
```

#### getMiningDifficulty

The number of digits that the digest of the PoW solution requires which typically auto adjusts during reward generation. Since it is an unsigned integer, fractional parts of the difficulty value are not provided.

``` js
function getMiningDifficulty() public constant returns (uint)
```

#### getMiningReward

Return the current reward amount. Depending on the algorithm, typically rewards are divided every reward era as tokens are mined to provide scarcity.

``` js
function getMiningReward() public constant returns (uint)
```

### Mining Debug Operations


#### getMintDigest

Returns a test digest using the same hashing scheme used when minting new tokens.

``` js
function getMintDigest(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number) public view returns (bytes32 digesttest)
```
**OPTIONAL** - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.


#### checkMintSolution

Verifies a sample solution using the same scheme as the mint method.

``` js
function checkMintSolution(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number, uint testTarget) public view returns (bool success) 
```
**OPTIONAL** - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

## Minting new BNbitcoin tokens

The BNbitcoin Token was deployed to the Binance Smart Chain blockchain in March, 2021, with the following attributes:
* No pre-mine
* No ICO
* 21,000,000 tokens total supply
* Difficulty target auto-adjusts with PoW hashrate
* Rewards decrease as more tokens are minted
* BEP20 compatibility

As such, the only way for a user to acquire BNBTC tokens is to mine them or purchase them from miners on decentralized/centralized exchanges. The mint function is responsible for verifying the validity of the hash solution, updating the contracts internal state and issuing new BNBTC tokens.

``` js
function mint(uint256 nonce, bytes32 challenge_digest) public returns (bool success) {   
    uint reward_amount = getMiningReward();

    bytes32 digest =  keccak256(challengeNumber, msg.sender, nonce );

    if (digest != challenge_digest) revert();

    //the digest must be smaller than the target
    if(uint256(digest) > miningTarget) revert();
 
    uint hashFound = rewardHashesFound[digest];
    rewardHashesFound[digest] = epochCount;
    if(hashFound != 0) revert();  //prevent the same answer from awarding twice

    balances[msg.sender] = balances[msg.sender].add(reward_amount);

    tokensMinted = tokensMinted.add(reward_amount);

    //set readonly diagnostics data
    lastRewardTo = msg.sender;
    lastRewardAmount = reward_amount;
    lastRewardEthBlockNumber = block.number;
    
    //start a new round of mining with a new 'challengeNumber'
     _startNewMiningEpoch();

    Mint(msg.sender, reward_amount, epochCount, challengeNumber );

    return true;
}
```
*figure 1. BNbitcoin Smart Contract mint() function*

The mining reward is initially gathered and follows the same algorithm as Bitcoin classic. Essentially following the paradigm of a decentralized monetary system, whereby the tokens are created by the nodes of a peer to peer network. The algorithm defines how the token will be created and at what rate.

As with Bitcoin, BNbitcoin tokens are generated every time a user discovers a new block by being the first to submit Proof of Work for each round. The rate of the block creation is adjusted every 2016. The amount of BNBTC generated per block is set to decrease logarithmically, having a 50% reduction every time half of the remaining supply has been mined (reproducing the so called "bitcoin halving"). This ensures that the total supply of BNBTC will never exceed 21 million. 

A unique 'nonce' has to be passed into the mint function along with the hash solution digest in order for tokens to be dispensed. To find this special number, it is necessary to run a mining program. More specifically, the PoW includes a recent BSC block hash combined with the wallet sender's address in order to prevent man in the middle attacks when minting new coins. The challenge and nonce are validated in solidity using the keccak256 hashing algorithm to decipher the challenge's digest. Once the digest has been extracted, it is validated to match the expected challenge result and then check to ensure that it is smaller than the mining target difficulty.

The mining reward is calculated based on the logarithmic halving algorithm, making the BNbitcoin token a predicable deflationary asset. The award is immediately assigned to the sender's wallet address and the ‘tokens minted count’ is incremented within the smart contract for any other software to monitor. Notably, the contract then validates that the tokens minted count is less than or equal to the maximum supply or the given halving era that transaction is taking place. Next, the contract records diagnostics reflecting reward address, amount and ether block number for the purpose of public transparency and for other software to monitor.

### Difficulty Calculation and Adjustment
After every block is minted, the smart contract will determine if it is time to adjust the difficulty.  This occurs every 2016 mined blocks.  Just before this occurs, the contract increments the reward era if necessary - this is, if the tokens minted count has exceeded the maximum era supply which is calculated via a simple halving algorithm: 

max_era_supply = total_supply - (total_supply / (2 * (reward_era + 1)))

This means that the first era supply is 10500000 tokens, the second era supply is 15750000 tokens, the third era supply is 18375000 tokens and so forth. During the first era, the block reward for a mint() is 50 tokens. During the second era, the reward is 25 tokens. During the third era, the reward is 12.5 tokens and so forth. There are forty eras total until the mining will halt. This is expected to take more than a century at which time BNbitcoin can be used as a decentralized digital currency for BSC.  

The reward era is used to calculate the mining reward.  Next, the BNbitcoin smart contract adjusts the difficulty by first determining how many BSC blocks had been mined since the last adjustment. Considering, like bitcoin, that the BNbitcoin block time should be 10 minutes (600 seconds) and the difficulty adjustment period should be 2 weeks, and considering that the Binance Smart Chain block time is 3 about 3 seconds, if less than 2016*200 BSC blocks had been mined BNbitcoin is being mined too quickly and the difficulty will increase.  This is accomplished by reducing the size of the ‘target’. When the target is smaller, valid nonces for minting are more rare and are harder to find for future mining rounds. Alternatively if BNbitcoin is being mined too slowly the target will increase in value in order to make minting more easy to accomplish.  All difficulty targets are bound within minimum and maximum difficulties of 2^16 and 2^224 respectively.

### Milestones and challenges 
BNbitcoin is implemented as a BSC BEP20 compatible token and so its success is largely dependent on the success of the Binance Smart Chain Network. In the midst of February 2021, Binance Smart Chain has demonstrated capable of sustaining a higher transactions volume than the Ethereum blockchain, while maintaining low gas fees and quicker transaction settlements. This fully reflects the reason why BNbitcoin has the lowest minting and transaction gas fees among the whole EVM-based mined tokens universe.     
  
### Frequently Asked Questions

#### Does BNbitcoin have its own Blockchain? 

No. BNbitcoin exists on the Binance Smart Chain as a Smart Contract. This allows it to leverage faster, more secure and more powerful applications natively with full security.

#### Why are there times when a lot of mints get reverted?

The difficulty was too low compared to hashrate and so multiple valid solutions were submitted to the contract in a very short amount of time.  Only one can be accepted each round and so the others are reverted.

#### How does the difficulty update?

Difficulty auto-updates during every 2016th mint in order to target a mint rate that is 200x slower than BSC block rate, or roughly 1 mint every 10 minutes.

#### Will there be a reward halvening event and when?

At 10.5m tokens mined and when half the remaining has been mined then half of that remaining then half of that remaining (and so on), up to 40 iterations. In other words, every 210000 mints. 

#### Since BNbitcoin is Proof of Work doesn't that mean it is bad for the environment?

As long as cryptocurrencies exists, mining will always exist.  Even though mining expends energy, it ultimately reduces corruption in society by providing humanity with decentralized and transparent transactional ledgers.  Therefore the idea similar to humanity having to pay for a gigantic decentralized accounting system or police network which is reducing the widespread financial corruption across the globe. Just as we pay police officers and accountants for their service, we 'pay' blockchains for their trust-minimizing corruption-reducing services in the form of energy and computation.

### Whitepaper Contributors

This whitepaper is forked from 0xBitcoin white-paper-v2, and credits go to the Authors.

Author of BNbitcoin: Ron_BNBTC.

### References

Satoshi Nakamoto. Bitcoin: A Peer-to-Peer Electronic Cash System, 2009. http://www.bitcoin.org/bitcoin.pdf.

BEP20 Standard (draft proposal): https://github.com/binance-chain/BEPs/blob/master/BEP20.md

0xBitcoin: https://0xbitcoin.org
