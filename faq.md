### Is there a PegNet whitepaper?

[Yes](https://pegnet.org/docs/whitepaper.html).

### What is PegNet?

<details><summary>View Answer (click here)</summary>
<p>

PegNet is a decentralized, non-custodial network of tokens pegged (stabilized) to different currencies and assets that allows for trading and conversion of value without the need for counterparties. It is a fully auditable, open-source stable coin network using the competition of PoW and external oracles to converge on the prices of currencies and assets.

</p>
</details>

### Why do assets begin with ‘p’? For example, pUSD, pEUR, pGLD?

<details><summary>View Answer (click here)</summary>
<p>

The PegNet is launching with 32 assets including 16 major currencies, 4 metals, and 12 cryptocurrencies. Each of these assets stands alone as a cryptocurrency token in the market and are designated with a leading ‘p’. For example: pUSD is pegged to the US Dollar

</p>
</details>

### What is the use case of PegNet?

<details><summary>View Answer (click here)</summary>
<p>

The use cases for pegged assets include payments, payment services, and store of value.

Payments in the broader market require a cryptocurrency denominated in real-world currencies like the US dollar, the Euro, Yen, Yuan, etc. The PegNet supports pegged tokens that represent currencies, metals, and other cryptocurrencies (each pegged asset acts as an independent cryptocurrency, but are members of the PegNet assets).

Payment services include the conversion of the PegNet asset used in payment to the PegNet asset required by the merchant. This allows the customer to pay in pEUR, pGLD, or pBTC, and the merchant can convert the payment to pUSD without a currency exchanger or any other 3rd party.

Traditionally, managing value is difficult and requires attention to the market. The PegNet allows value to be managed against a range of 32 or more assets without involving 2nd or 3rd parties.

The nature of PegNet and its lack of counterparty opens up new implementations for the cryptocurrency industry such as simplified smart contract settlement and novel DEX liquidity mechanisms.

</p>
</details>

### What blockchain does PegNet utilize?

PegNet is built on top of the Factom Protocol.

### Has a regulatory analysis been performed on PegNet?

[Yes](https://docs.google.com/document/d/1es1_VNGOHhwC_aqoSq_G3bf9LvovRvhGc9XaC8rEu6c/edit?usp=sharing).

### What currencies and assets currently are part of PegNet?

<details><summary>View Answer (click here)</summary>
<p>

The current proposed set includes:

| Currencies       | Precious Metals | Cryptocurrencies       |
| ---------------- | --------------- | ---------------------- |
| US Dollar        | Gold            | PEG (The PegNet Token) |
| Euro             | Silver          | Bitcoin                |
| Japanese Yen     |                 | Ethereum               |
| British Pound    |                 | Dash                   |
| Canadian Dollar  |                 | Bitcoin Cash           |
| Swiss Franc      |                 | Binance Coin           |
| Indian Rupee     |                 | Stellar                |
| Singapore Dollar |                 | Cardano                |
| Chinese Yuan     |                 | Monero                 |
| Hong Kong Dollar |                 | Zcash                  |
| Tiawanese Dollar |                 | Decred                 |
| Korean Won       |                 | Litecoin               |
| Mexican Peso     |                 | Ravencoin              |
| Brazillian Peso  |                 | Factom                 |
| Phillipine Peso  |                 |                        |
|                  |                 |                        |

</p>
</details>

### What is PEG?

<details><summary>View Answer (click here)</summary>
<p>

Peg Network Token (PEG) is the PegNet token that summarizes the value of the set of pegged tokens in the market. The market value of all the pegged assets, divided by the number of existing PEG is used to set the value of PEG prior to exchanges establishing a market price. PEG can be converted into any pegged asset and any pegged asset can be converted into PEG. For example, if the value of one PEG is \$2.00 you could convert it into two pUSD.

Conversion involves burning the asset you are contributing and issuing the asset that you want. This is done in the context of the prices in USD for the assets involved, as determined by the market price.

</p>
</details>

### How is the value of assets like Gold determined by the network?

<details><summary>View Answer (click here)</summary>
<p>

External oracles are used. In fact, that data is what the miners “mine”. Anyone that wants to mine prices for the PegNet can use their computers to mine price data. This price data collected into an Oracle Price Record (OPR). The OPRs are sorted by Proof of Work (PoW) and the highest 50 are then evaluated for agreement. The record that most agrees with the rest of the 50 records provides the prices for the current block. The top 10 OPRs in most agreement all receive rewards.

</p>
</details>

### What are the PegNet’s tokenomics?

<details><summary>View Answer (click here)</summary>
<p>

Outside of exchange listings, the two onramps into the PegNet are mining PEG and burning FCT (the token of the Factom Protocol) for pFCT. PEG (Peg Network Token) is the PegNet token that summarizes the value of the set of pegged tokens in the market. The market value of all the pegged assets divided by the number of existing PEG is used to set the value of PEG until exchanges set its value. PEG can be burned into any pegged asset. For example, if the value of one PEG is \$2.00 you could burn it into two pUSD (the pegged token for US Dollars). Burning that PEG would reduce the supply of PEG and increase the total value of pegged assets thus increasing the value of remaining PEG. If you burn 100 FCT it creates 100 pFCT. You may then convert the 100 pFCT to pUSD or pBTC or any other asset at the oracle defined market price. When you convert to a new token, the old token is burned (destroyed). Any pegged token may also be burned into PEG.

</p>
</details>

### Why is PegNet superior to custodian or ethereum smart contract based stable coins?

<details><summary>View Answer (click here)</summary>
<p>

Reserve based assets do not support the conversion between assets. The user is restricted to the liquidity of the reserve assets held on an exchange. The same is true for Ethereum smart contract based stable coins. Further, reserve based coins are not decentralized, and their viability is defined by the banks and institutions that hold their reserves.

Smart contract based stable coins are decentralized to a great degree but involve leverage contracts that achieve stability through liquidation when the market pressure is forcing asset prices down. Further, smart contract coins are very complicated and it is hard to understand their implementation.

The PegNet only provides conversions between pegged assets. This is something neither reserve tokens or smart contract tokens can do, provides for payments and payment services, is decentralized, and works in bull and bear markets.

How is price stability maintained on exchanges?  
Via arbitrage. For example, on an exchange, if pUSD dropped to $0.95, then it could be purchased at the discount (thus raising the price) while simultaneously burning pUSD at the $1.00 set by the external oracle within PegNet. With arbitrage, the profits can be left in any asset on the exchanges, such as USD, BTC, or any other asset.

</p>
</details>

### How many PEG are rewarded per block?

<details><summary>View Answer (click here)</summary>
<p>

5,000 PEG to 10 different miners. The best miner receives 800, second receives 600, and the other eight receive 450. Block times are 10 minutes (the block time of the Factom Protocol which PegNet is built on top of). The reward per block is not reduced over time.

</p>
</details>

### How do I start mining?

See the [mining documentation](./Mining).

### I want to hold pBTC, pFCT, and pGold. Will I need three separate addresses?

<details><summary>View Answer (click here)</summary>
<p>

All PegNet assets are based on Factoid addresses. The same Factoid Address holds the ability to sign Factoid transactions, pBTC, pFCT, and pGold transactions. So the Factoid address can be considered the root address that can none the less hold many other balances.

</p>
</details>

### Why should our exchange list PegNet tokens?

<details><summary>View Answer (click here)</summary>
<p>

PegNet is a mined token system, so miners do need a place to sell their tokens. Further, PegNet is fueled by arbitrage, which generates trades and liquidity. Because of the arbitrage, Exchanges will make more in transaction fees than with other, more difficult to arbitrage tokens and coins. Because of the flexibility of conversion in the PegNet, some exchanges will eventually support on-exchange conversions, adding to liquidity, arbitrage. Such flexibility will encourage merchant and user integration with exchanges.

</p>
</details>

### I represent an exchange that would like to list PEG or other PegNet tokens. What is the process?

<details><summary>View Answer (click here)</summary>
<p>

PegNet is not controlled by anyone and cannot pay a listing fee. If you need technical assistance implementing PegNet tokens on your exchange, please ask for help on our [Discord](https://discord.gg/V6T7mCW).

</p>
</details>

### How do you burn FCT (the token of the Factom Protocol) for pFCT?

<details><summary>View Answer (click here)</summary>
<p>

You will be able to burn FCT to pFCT by using a special command in the PegNet command-line interpreter (pncli). 100 FCT will be converted into 100 pFCT.

</p>
</details>

### Who controls PegNet?

<details><summary>View Answer (click here)</summary>
<p>

Nobody controls PegNet. It is a decentralized system built on top of the Factom Protocol. Anyone can contribute to the Core code and run a miner.

</p>
</details>

### Where can I discuss PegNet with others?

[Discord](https://discord.gg/V6T7mCW) and [Reddit](https://www.reddit.com/r/PegNet/)

### How long do transactions (sending an asset to another address) take and how long do conversions (converting one pAsset to another pAsset) take?

<details><summary>View Answer (click here)</summary>
<p>

Transactions take a maximum of 10 minutes on the network.  Conversions take at least 10 minutes but not more than 20 minutes.

</p>
</details>

### If I initiate a conversion, is it priced based upon current oracle data?

<details><summary>View Answer (click here)</summary>
<p>

No.  Once you initiate a conversion, the system waits until the next block and uses that price data.  That's why conversions take at least 10 minutes but not more than 20.  This avoids people taking advantage of old pricing data.

</p>
</details>
