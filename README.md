## 0xBitcoin  

#### ( Whitepaper Revision 2.0.0 )

#### 0xBitcoin: The Credibly Neutral Mineable Token for Ethereum 
-------------------------------

### Abstract 
This paper describes the Pure Mined ERC20 token 0xBitcoin (0xBTC).  This EVM-based cryptocurrency was deployed to the Ethereum EVM using the Solidity language and it is designed to be trust-minimized and verifiably credibly-neutral by borrowing from the ideals of the original Bitcoin Whitepaper (Satoshi, 2009).  'Trust-minimized' in this context means that the holders of 0xBTC are exposed to absolutely as little human-decision-based risk as possible.  'Verifiably credibly neutral' means that users can self-verify that the creation and distribution of 0xBTC was mathematically 'fair' and transparent, only being based on Proof-of-Work, the expenditure of energy, and knowledge of the currency.  No knowledge of human intent, behavior, or off-chain action is needed to prove that 0xBTC is a neutral currency and/or fairly distributed without bias.  'Native' means that the currency is in its basic form, not reliant on centralized Oracles, external non-Ethereum Consensus, or private keys held by centralized individuals.  The economic security of 0xBTC is only limited to that of the economic security of Ethereum.  It should be noted that 0xBTC is not reliant on any centralized private keys and this is core to the thesis.


### Background
The Ethereum Network has proven itself as the world’s first ecosystem for permissionless, transparent and immutable software applications.  These software applications, in the form of Smart Contracts, all interact with one other.  Many standard protocols have been developed such as the ERC20 standard for a common ‘token’ format so that these Smart Contracts can pass scarce, owned, and transferable value between one another without a centralized third-party.  Up until 2018, every ERC20 token had been distributed in a matter that is generally known to align with ‘securities.’  The tokens are sold to ‘investors’ by the ‘creator’ under the pretenses that the ‘creator’ will perform some action to make the tokens more valuable.  It should be clarified that Bitcoin is distributed via ‘bitcoin mining’ and therefore aligns itself as a ‘commodity’ and not a ‘security.’  

This whitepaper will describe the first ERC20 token that aligns itself as a ‘commodity’ since it is distributed only using ‘Proof of Work Mining’ identical to the model introduced in the Bitcoin White Paper (Satoshi, 2009).  It is an open source community project, not led by an official team or corporation, and therefore does not have ICO capital or other vast amounts of currency/capital that a centralized token project would have.  We believe as a community that decentralization is the true flavor of the blockchain and that is the architecture that provides open and transparent trust for users.  We also believe that Ethereum and ERC20 tokens are a significant segment of the future of blockchain technology.

The 0xBitcoin token (0xBTC) is similar to a fork of Bitcoin in that it does not share the price, liquidity or supply with Bitcoin.  It is a re-genesis of the Bitcoin protocol natively on the Ethereum EVM.  This gives 0xBTC several advantages over Bitcoin, which does not exist in the Ethereum EVM, and over Bitcoin Synthetics (wBTC, renBTC, tBTC) which do exist within the Ethereum EVM but which introduce new assumptions, low economic ceilings, and trust-related risks that directly conflict with the nature of Bitcoin.  This is elaborated upon in the section titled 'Comparison to Synthetics'.


### Name Origin of 0xBitcoin
The name 0xBitcoin is derived from a combination of the name of the decentralized and mined commodity Bitcoin with the term ‘0x’ which implies that the asset lives on the Ethereum Network.  This is implied because all Ethereum addresses begin with the characters ‘0x.’  The 0xBitcoin contract is located at Ethereum address [0xb6ed7644c69416d67b522e20bc294a9a9b405b31](https://etherscan.io/address/0xb6ed7644c69416d67b522e20bc294a9a9b405b31) and has validated transparent code which can be audited on the Etherscan.io website.  


### Ethereum and ICOs	
The Ethereum blockchain in its current state exists as a thriving permissionless ecosystem which allows any individual to store immutable records in a permissionless, invulnerable and transparent manner.  There is no other database system in the world that has this ability except for Ethereum and other similar blockchains.  As blockchain applications become richer and more numerous, there is a need for alternative distribution models than the ICO. Indeed, there have been proposals to mitigate some  initial investment risks through the recent introduction of the DAICO model (Cunningham, 2018) that rely on timed and automated value transfers via the DIACO smart contract tapping mechanism. However, this does not align a token smart contract as a non-security and still has the potential to put investors at risk if not implemented carefully. Allowing users of the network direct access to tokens by performing computations as a proof of work supplies allows any smart contract to distribute a token in a safe, slow, and controlled manner similar to the release of a new commodity.

Ethereum token distribution methods such as 'Airdrops' and 'Initial Coin Offerings' (ICOs/IEOs) which do not use Proof of Work are fundamentally flawed and are able to be Sybil-attacked and Insider-knowledge-attacked.  A Sybil attack is a form of computer security attack in which one human pretends to be many humans with multiple computer accounts in order to manipulate a system in a malicious way.  An insider attack is the use of insider information in order to secretly gain an upper hand or advantage during the distribution of a currency.  ICOs and airdrops are highly susceptible to Sybil Attacks and Insider-Knowledge Attacks and there is no way to verify that all ERC20 tokens were distributed by the deployer fairly using on-chain data.  0xBTC, with its unique Proof of Work distribution method, has distribution which is purely mathematical and which can be completely verified all on-chain.  This makes 0xBTC the first credibly-neutral, self-verifiable and pure mined native currency in the Ethereum EVM.  It can be publicly verified that the distribution of 0xBTC is fair since, by reading just the Solidity contract and its transactions, it is clear that 0xBTC has only been distributed by mathematical PoW hashing and not by any external means or coordination through a central party/account.


### Current and Proposed Use Cases
By implementing the ERC20 token protocol and combining it with Nakamoto Proof of Work distribution in an Ethereum Smart Contract, 0xBTC combines advantages from both Bitcoin and Ethereum.  The asset is decentralized, permissionless, mined and scarce such that it is a transparent and permanent digital record of transferrable value.  Additionally, 0xBTC has the speed and scalability of the Ethereum network and is compatible with all ERC20 token services.  Following the ERC20 protocol natively, 0xBTC can be stored in any Ethereum wallet, is as secure as any Ethereum asset, and is credibly neutral verifiable currency.  This is important because Bitcoin is not able to communicate with or interact with the Ethereum smart contract ecosystem without an intermediate Proof of Stake consensus network with lesser economic security than that of Ethereum Network.  With 0xBTC, the Ethereum network is now effectively upgraded with an internal pure-mined and trustless commodity.  
 

### Native Support for Decentralized Exchange
Since it follows ERC20 protocol, 0xBTC can natively interact with decentralized exchanges such as Uniswap and ForkDelta since it is compatible with Ethereum smart contracts.  This means that while native Bitcoin can only be traded using centralized means, 0xBTC can be traded permissionlessly within immutable permanent smart contracts which are not able to be censored or restricted by central entities. 


### Account System 
As an ERC20 token, 0xBTC uses a traditional Ethereum account. These accounts are free and are impossible to hack or to steal from, given that the private key has not been exposed.  0xBTC does not manage its own network and requires fees denominated in Ether, paid to Ethereum Validators, to transfer and to mine.  


### Network Security
0xBTC does not operate its own chain or network.  The mining of 0xBTC only affects the supply and is a means-to-an-end to ensure that 0xBTC is a verifiably neutral and decentralized currency with no centralized leader, stakeholder, or team.  Since 0xBTC is a smart contract within Ethereum Mainnet, it has the full security of Ethereum Mainnet.  In order to double spend or 51% attack 0xBTC transactions, the entire Ethereum Mainnet would have to be double spent and rolled back with a 51% attack.   This is completely unrelated to the hashrate or PoW mining power of 0xBTC.  


---

### Comparison to Synthetics
As a new re-genesis, 0xBTC does not have the liquidity or the original chain-data of 'Bitcoin'.  However, this allows 0xBTC to be trust-minimized and to have the properties of 'Bitcoin' as an unstoppable, immutable, decentralized pure-mined cryptocurrency which is free from Oracles, external Consensus, and centralized keys.  

Since 2018, several 'Bitcoin Synthetics' have been deployed to the Ethereum EVM such as wBTC, tBTC, and renBTC.  These currencies sacrifice the trustless and immutable nature of native Bitcoin in order to import the price and liquidity of Bitcoin into the Ethereum EVM.  We are concerned because these synethetics all increase trust-based risk and introduce new centralized attack vectors in different ways, thus putting holders funds in jeopardy as compared to the users holding native Bitcoin or native 0xBTC.


#### WBTC 
In the case of wBTC, centralized private keys are used to arbitrarily mint and burn wBTC as to the will of the anonymous holders of those keys.  We are primarly concerned that at any time, wBTC in any amount can be created and sold, even in a single transaction, debasing the entire asset and stealing wBTC holder funds with no warning.  Comparitively, 0xBTC does not rely on any private keys for any function.  

    Reference: https://etherscan.io/token/0x2260fac5e5542a773aa44fbcfedf7c193bc2c599#readContract


#### RENBTC
In the cases of renBTC, an external Proof-Of-Stake (PoS) consensus blockchain is used ('The DarkNodes') which has the authority to mint and burn renBTC at the will of the majority consensus of this PoS blockchain.  As long as only a small supply of renBTC is being secure by this chain, it is not profitable for a rogue party to hijack the consensus of this separate PoS blockchain.  This means that renBTC is capped below a maximum total supply.  Our concern is that, if the total supply of renBTC (Locked) were to exceed the value of REN bonded (Bonded) then it would be profitable for a rogue entity to stake enough bonded liquidity to hijack the network and steal the Locked value, debasing the asset and stealing renBTC holder funds with no warning.  This Locked vs Bonded ratio is described in renBTC whitepaper, and they deem a 3x ratio to be safe.  Comparatively, 0xBTC is infinitely economically scaleable with no detriments to security.   

    Reference: https://republicprotocol.github.io/whitepaper/republic-whitepaper.pdf


#### TBTC 
In the case of tBTC, the system operates in largely the same methology as renBTC.  A group of 'signers' with bonded stake (tBTC v1 uses ETH for PoS consensus) are used to verify bonds of BTC and ETH alongside a Price Oracle.  These 'signer nodes' use Proof of Stake consensus and have the full authority to mint or burn new tBTC at any time, for any reason they deem fit.  This also allows them to 'abscond' with funds, meaning the signers can collude to steal the underlying liquidity of tBTC and debase the entire asset, stealing user funds. As long as the total amount of tBTC secured by this consensus remains below the ceiling of safety of the staked asset (staked ETH by signers) (Locked vs Bonded) then it is not profitable for an attacker to hijack the network in this way.   Comparatively, 0xBTC is infinitely economically scaleable with no detriments to security.    

    Reference: https://docs.keep.network/tbtc/index.pdf 

---

### Mining
The methodology by which 0xBTC is PoW mined follows the metholody of mining Bitcoin identically.  A number 'nonce' must be found which when hashed with other data will result in a digest 'D' which is less than target 'T'.  The difficulty of ‘mining’ this commodity automatically adjusts to the total computational power that is actively mining. 

There have been other mintable or mined tokens proposed for Ethereum before 0xBTC but none of them had successfully implemented Proof of Work gated mints with automated difficulty adjustment.  0xBTC is mined using the simple Keccak256 (Sha3) algorithm using the following methodology:


``` js
   keccak256(nonce, minerEthAddress, challengeNumber) < difficultyTarget
```

The nonce is a random number selected by the mining software.  The mining software mines to try to find a valid nonce.  If the above statement evalutates to true, then the nonce is a valid solution to the proof of work.   The challengeNumber is just a recent Ethereum block hash.  Every round, the challengeNumber updates to the most recent Ethereum block hash so future works cannot be mined in the past.  The miner's Ethereum Address is part of the hashed solution so that when a nonce solution is found, it is only valid for that particular miner and man in the middle attacks cannot occur.  This also enables pool mining.  The difficulty target becomes smaller and smaller automatically as more hashpower is added to the network.

### Pool Mining 
When mining 0xBitcoin, whenever a miner submits a solution, the miner must pay a small gas fee in order to execute the Ethereum smart contract code for the mint() function.  If the gas fee is too low, the solution will take too long to be mined and if difficulty is not at equillibrium then another mint() solution from another miner will likely be mined first.  This renders the original miners solution invalid and the transaction will revert().  To alleviate gas fees for miners, they can instead mine into a pool.  This way, the pool will then submit the solutions to the smart contract and pay a gas fee.  Then the pool will typically take a small percent of the rewards and give the rest to the miner for providing the PoW solution.  

Since the miner's ethereum address is included in the proof of work, pools require that miners mine using the pool's ethereum address.  This way, the miner cannot submit full solutions to the contract while only giving partial solutions to the pool.  If the miner is mining on behalf of the pool (using the pools address in the PoW algorithm) then it will not be able to submit any of those solutions to the smart contract without a revert().  This allows pools to operate without being cheated by the miners.     

Typically, a pool will accept 'partial solutions' from miners which means the miners will receive 'shares' from the pool for solutions that are close to valid but not quite valid.  This follows the same methodology as Bitcoin and Ethereum Proof of Work pool mining.  Probability theory states that, given enough close solutions, a full solution will eventually be found.  

### Smart Contract
Typically, ERC20 tokens will grant all tokens to the owner or will have an ICO which demands that amounts of Ether be sent to the owner for an initial offering of tokens.  Instead of granting tokens to the 'contract owner', all 0xBitcoin tokens are locked within the smart contract initially. These tokens are dispensed, 50 at a time, by calling the function 'mint' and using Proof of Work, similar to mining bitcoin classic. The 0xBitcoin smart contract is the first token to adhere to the ERC541 Draft Specification. As such the following Smart Contract methods are explicitly supported:

## Token
### ERC-20 Interface
#### name

Returns the name of the token - e.g. `"0xBitcoin Token"`.

OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function name() constant returns (string name)
```

#### symbol

Returns the symbol of the token. e.g. `"0xBTC"`.

OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function symbol() constant returns (string symbol)
```

#### totalSupply

Returns the total token supply.

``` js
function totalSupply() constant returns (uint256 totalSupply)
```

#### balanceOf

Returns the account balance of another account with address `_owner`.

``` js
function balanceOf(address _owner) constant returns (uint256 balance)
```

### Mining Operations


#### mint

Returns a flag indicating a successful hash digest verification. In order to prevent MiTM attacks, it is recommended that the digest include a recent ethereum block hash and msg.sender's address. Once verified, the mint function calculates and delivers a mining reward to the sender and performs internal accounting operations on the contract's supply.

``` js
function mint(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

##### *Mint Event*

Upon successful verification and reward the mint method dispatches a Mint Event indicating the reward address, the reward amount, the epoch count and newest challenge number.

``` js
event Mint(address indexed from, uint reward_amount, uint epochCount, bytes32 newChallengeNumber);
```

#### getChallengeNumber

Recent ethereum block hash, used to prevent pre-mining future blocks.

``` js
function getChallengeNumber() public constant returns (bytes32) 
```

#### getMiningDifficulty

The number of digits that the digest of the PoW solution requires which typically auto adjusts during reward generation.Return the current reward amount. Depending on the algorithm, typically rewards are divided every reward era as tokens are mined to provide scarcity.


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
OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.


#### checkMintSolution

Verifies a sample solution using the same scheme as the mint method.

``` js
function checkMintSolution(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number, uint testTarget) public view returns (bool success) 
```
OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

## Minting New 0xBitcoins

The 0xBitcoin Token was deployed to the Ethereum blockchain in February, 2018, with the following attributes:
* No pre-mine
* No ICO
* 21,000,000 tokens total supply
* Difficulty target auto-adjusts with PoW hashrate
* Rewards decrease as more tokens are minted
* ERC20 compatibility

As such, the only way for a user to acquire 0xBitcoins is to mine them or purchase them from miners on decentralized/centralized exchanges. The mint function is responsible for verifying the validity of the hash solution, updating the contracts internal state and issuing new 0xBitcoins.

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
*figure 1. 0xBitcoin Smart Contract mint() function*

The mining reward is initially gathered and follows the same algorithm as Bitcoin classic. Essentially following the paradigm of a fully decentralized monetary system, whereby the tokens are created by the nodes of a peer to peer network. The algorithm defines how the token will be created and at what rate.

As with Bitcoin, 0xBitcoins are generated every time a user discovers a new block by being the first to submit Proof of Work for each round. The rate of the block creation is adjusted every 1024 to aim for a relatively constant adjustment period equal to approximately 1 0xBTC mint per 60 ETH blocks, or roughly 6 per hour. The amount of 0xBTC generated per block is set to decrease logarithmically, having a 50% reduction every time half of the remaining supply has been mined.  This ensures that the total supply of 0xBTC will never exceed 21 million. 

A unique 'nonce' has to be passed into the mint function along with the hash solution digest in order for tokens to be dispensed. To find this special number, it is necessary to run a mining program. More specifically, the PoW includes a recent Ethereum block hash combined with the wallet sender's address in order to prevent man in the middle attacks when minting new coins. The challenge and nonce are validated in solidity using the keccak256 hashing algorithm to decipher the challenge's digest. Once the digest has been extracted, it is validated to match the expected challenge result and then check to ensure that it is smaller than the mining target difficulty.

The mining reward is calculated based on the logarithmic halving algorithm making the 0xBitcoin token a predicable deflationary asset. The award is immediately assigned to the sender's wallet address and the ‘tokens minted count’ is incremented within the smart contract for any other software to monitor. Notably, the contract then validates that the tokens minted count is less than or equal to the maximum supply or the given halving era that transaction is taking place. Next, the contract records diagnostics reflecting reward address, amount and ether block number for the purpose of public transparency and for other software to monitor.

### Difficulty Calculation and Adjustment
After every block is minted, the smart contract will determine if it is time to adjust the difficulty.  This occurs every 1024 mined blocks.  Just before this occurs, the contract increments the reward era if necessary - this is, if the tokens minted count has exceeded the maximum era supply which is calculated via a simple halving algorithm: 

max_era_supply = total_supply - (total_supply / (2 * (reward_era + 1)))

This means that the first era supply is 10500000 tokens, the second era supply is 15750000 tokens, the third era supply is 18375000 tokens and so forth.   During the first era, the block reward for a mint() is 50 tokens.  During the second era, the reward is 25 tokens.  During the third era, the reward is 12.5 tokens and so forth.  There are forty eras total until the mining will halt.  This is expected to take about 100 years at which time 0xBitcoin can be used as a decentralized digital currency for Ethereum.  

The reward era is used to calculate the mining reward.  Next, the 0xBitcoin smart contract adjusts the difficulty by first determining how many Ethereum blocks had been mined since the last adjustment.  If less than 1024*60 Ethereum blocks had been mined, 0xBitcoin is being mined too quickly and the difficulty will increase.  This is accomplished by reducing the size of the ‘target’.  When the target is smaller, valid nonces for minting are more rare and are harder to find for future mining rounds.   Alternatively if 0xBitcoin is being mined too slowly the target will increase in value in order to make minting more easy to accomplish.  All difficulty targets are bound within minimum and maximum difficulties of 216 and 2234 respectively.

### Calculating Mining Hashrate
To calculate approximate hashrate or approximate time to find a solution, the following equation can be used:

	TimeToSolveBlock (seconds) = (difficulty * 2 ^ 22) / hashrate (hashes per second)
 
 

### Risks and Challenges 
0xBitcoin is implemented as an Ethereum ERC20 token and so its success is largely dependent on the success of the Ethereum Network.  If Ethereum cannot scale using methods such as Plasma, Casper, and the Loom network, then 0xBitcoin will not be able to realize its full potential as the fastest and most effective decentralized currency in the world.   
  
### Frequently Asked Questions

#### Does 0xBitcoin have its own Blockchain? 

No. 0xBitcoin exists on the Ethereum Blockchain as a Smart Contract. This allows it to leverage faster, more secure and more powerful applications natively with full security.

#### Why are there times when a lot of mints get reverted?

The difficulty was too low compared to hashrate and so multiple valid solutions were submitted to the contract in a very short amount of time.  Only one can be accepted each round and so the others are reverted.

#### How does pool mining work with 0xBitcoin?

Essentially the same way that pool mining works for classic Bitcoin, except 0xBitcoin pools must pay gas fees to the Ethereum network.  

#### How does the difficulty update?

Difficulty auto-updates during every 1024th mint in order to target a mint rate that is 60x slower than eth block rate, or roughly 1 mint every 15 minutes.

#### Will there be a reward halvening event and when?

At 10.5m tokens mined and when half the remaining has been mined then half of that remaining then half of that remaining (and so on), up to 40 iterations.  In other words, every 210000 mints. 

#### Since 0xBitcoin is Proof of Work doesn't that mean it is bad for the environment?

As long as cryptocurrencies exists, mining will always exist.  Even though mining expends energy, it ultimately reduces corruption in society by providing humanity with decentralized and transparent transactional ledgers.  Therefore the idea similar to humanity having to pay for a gigantic decentralized accounting system or police network which is reducing the widespread financial corruption across the globe.  Just as we pay police officers and accountants for their service, we 'pay' blockchains for their trust-minimizing corruption-reducing services in the form of energy and computation.

### Whitepaper Contributors
1. Infernal_toast (contract deployer)
2. Jay Logelin (jlogelin@fas.harvard.edu)

### References

Satoshi Nakamoto. Bitcoin: A Peer-to-Peer Electronic Cash System, 2009. http://www.bitcoin.org/bitcoin.pdf.

Logelin J and 0xBitcoin communitiy members. ERC 541 - Mineable Token Standard Draft, 2018. https://github.com/ethereum/EIPs/pull/918

Fabian Vogelsteller and Vitalik Buterin. ERC-20 Token Standard, 2015. URL https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20-token-standard.md.

TrustNodes. The First PoW Bitcoin Like Token Launches on Ethereum, February 16, 2018. https://www.trustnodes.com/2018/02/16/first-pow-bitcoin-like-token-launches-ethereum

Vitalik Buterin. Ethereum White Paper, 2014. https://github.com/ethereum/wiki/wiki/White-Paper

Epstien J. Why Proof of Work in Bitcoin Means Proof of Value in the Real World, December 20, 2017. https://www.neverstopmarketing.com/proof-work-bitcoin-means-proof-value-real-world/

Bitfury Group Limited. "Proof of Stake versus Proof of Work", 2015. http://bitfury.com/content/5-white-papers-research/pos-vs-pow-1.0.2.pdf

https://en.bitcoin.it/wiki/Controlled_supply

Dai W. "b-money", 1998. http://www.weidai.com/bmoney.txt

Back A. "Hashcash - a denial of service counter-measure", 2002. http://www.hashcash.org/papers/hashcash.pdf

Cunningham A, Ethereum Co-Founder Announces DAICO, a new ICO Fundraising Model (January 15, 2018). https://discover.coinsquare.io/investing/daico-new-ico-fundraising-model/

