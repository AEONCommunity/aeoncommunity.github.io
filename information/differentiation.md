---
permalink: ./information/differentiation.html
---

<h1>AEON Differentiation</h1>
<p><b>(Last updated February 19, 2019)</b></p>

<p>With the astounding plethora of “alt coins” now available, it is worth noting how AEON differs from others, and specifically how it improves upon some of the similar offerings.</p>

<p>The first thing to note is that within the alt coin universe, there are different classes of blockchain and coin.  There are <b>smart contract</b> blockchains (i.e. Ethereum) which provide a mechanism to manage complex transactions such as business contracts and decentralized application (“dApp") hosting.  There are also <b>token</b> coins (i.e. STEEM token) which supply a payment mechanism for use of a particular decentralized application or service.</p>

<p>AEON is a <b>currency</b> coin, intended to provide an alternative to local fiat currencies.  Therefore, this section will provide comparisons only to other well-known currency coins:  Bitcoin, Litecoin, Monero, Dash, Zcash, and Ripple.</p>


<h2>vs. Bitcoin</h2>
<p>Bitcoin is the best-known of all crypto currency blockchains, as it was the first to achieve a measure of success. There are considerable differences between AEON and Bitcoin, in the areas of privacy and usability.</p>

<h3>Privacy and Transaction Linkages</h3>
<p>Regarding the critical feature of privacy, Bitcoin falls short of the AEON blockchain. In order to maintain privacy of individual expenditures, it must be exceedingly difficult for an outside party to link a transaction back to its owner.</p>

<p>Consider that each transaction consists of some <i>inputs</i> (coins which are being spent) and some <i>outputs</i> (one or more addresses which receive the spent coins).  Additionally, each input in a transaction actually links to an output of a <i>previous</i> transaction, forming a set of transaction paths.</p>

<p>In Bitcoin, these transaction linkages are explicitly transparent on the blockchain. Any blockchain explorer can follow the graph, which has allowed for sophisticated analysis to de-anonymize transactions. This privacy issue is alleviated in various ways, such as creating a unique address for every transaction, using centralized “mixers" to randomly “mix up" several people's Bitcoins, and employing methods to hide IP addresses when making transactions.  The fact remains, however, that the Bitcoin inputs and outputs can be directly followed on the blockchain.</p>

<p>AEON resolves this privacy concern by <i>intentionally obscuring</i> transaction linkages on the blockchain. Every transaction has a default number of “decoy" input links (also known as <b>mixins</b>). Anyone making a transaction can request a higher number of decoy inputs, to increase anonymity.  As the blockchain grows over time, the increasing number of decoy input links will make the overall graph of transactions exceedingly difficult, if not impossible, to correctly decipher.</p>

<h3>Mining and Barriers to Participation</h3>
<p>Bitcoin uses a SHA-256 Proof-of-Work (PoW) algorithm which is dependent primarily on CPU power, and there are several specialized ASIC hardware devices made for mining Bitcoin. This has driven the hashrate high enough that currently only ASIC hardware mining is profitable.  The result is that the average person with a PC cannot readily participate in the transaction validation process of mining and acquiring Bitcoins.</p>

<p>AEON uses a CPU-friendly PoW algorithm that limits the advantage of GPU’s and is ASIC resistant. This allows almost anyone with a PC to participate in mining and acquiring AEON.</p> 

<h3>General Usability and Transactions-Per-Second</h3>
<p>Regarding usability and the vision of a lightweight digital currency for everyone, AEON has distinct advantages over Bitcoin.</p>

<p>The original Bitcoin block size (maximum of 1 MB) and the block creation time of 10 minutes limited the transactions-per-second (TPS) processing power to no more than 7 TPS.  This low TPS severely hindered the ability of the Bitcoin blockchain to process the necessary volume of transactions.</p>

<p>In August of 2017 the Bitcoin blockchain implemented a change known as "Segwit" (short for Segregated Witness) which effectively doubles the block size from 1 MB to 2 MB. Thus, the transaction processing power has been doubled, to 14 TPS.  There is a change in the works called Segwit2x which would double the effective block size again, bringing the Bitcoin processing power to 28 transactions per second.  While this is a marked improvement, the TPS is still too low for Bitcoin to become a currency for the masses.</p>

<p>For comparison, credit card processors typically see an average of 1700 transactions per second, with peaks of 3000 to 4000.  Paypal's average is just under 200 TPS.  Bitcoin's low TPS will cause it to become more of a high-end investment with limited use as a currency, not unlike physical gold coins versus U.S. dollar bills.</p>

<p>AEON solves the TPS limitation by using an algorithm to automatically adjust the maximum block size up or down, based on the previous 100 blocks. This approach allows the AEON blockchain to self-adjust it's TPS throughput as transaction traffic increases and decreases over time.</p>

<h2>vs. Litecoin</h2>
<p>Litecoin was started as a fork of the Bitcoin code in 2011, with the goal of being a lighter-weight currency, offering low-cost transactions with fast confirmation status.</p>

<h3>Privacy and Transaction Linkages</h3>
<p>See the description of the privacy issues in section <i>vs. Bitcoin</i>. Litecoin has the same issues as Bitcoin.</p>

<p>Charlie Lee, the creator of Litecoin, is actively researching options to bring more privacy to Litecoin.  This would presumably be accomplished with significant changes to the underlying protocol, and would be an interesting development for the coin.  It is unknown what impact the changes would have on other aspects such as block size, transaction size, and TPS.</p>

<h3>Mining and Barriers to Participation</h3>
<p>Litecoin uses a Proof-of-Work algorithm called <b>scrypt</b> which depends not only on the CPU, but also on fast access to a memory area.  At first, this PoW made it difficult to develop specialized ASIC hardware. In recent years, however, scrypt-capable ASICs have been developed which can efficiently mine any cryptocurrency that uses the scrypt algorithm. Thus, just like Bitcoin, the average person with a PC cannot successfully participate in the process of mining and acquiring Litecoin.</p>

<p>AEON actually uses an improved version of the scrypt algorithm which employs a larger memory area. The result is that AEON is even more resistant than Litecoin to specialized hardware, and the GPU cards do not have as great an advantage over the CPU.  This ensures that CPU mining with an average PC is an option for everyone.</p>

<h3>General Usability and Transactions-Per-Second</h3>
<p>Being a “lightweight Bitcoin" it is no surprise that Litecoin is able to boast a higher TPS than Bitcoin. The maximum transaction throughput is currently 56 transactions per second. (Remember that credit card processors can see peaks up to 4000 TPS.) While the Litecoin network can currently process transactions fast enough for its volume of users, at some point -- long before Litecoin can become a currency for the masses -- its TPS must be greatly increased.</p>

<p>See the prior section <i>vs. Bitcoin</i> for a description of AEON's solution to the TPS limitation.</p>

<h2>vs. Monero</h2>
<p>It is public knowledge that AEON is a fork of the Monero project, and it continues to incorporate improvements directly from the Monero code base.  In fact, the Development team for AEON consists largely of Monero developers who also work on AEON.  Since Monero itself is well-known as a security/privacy coin, it requires some attention, to address exactly why AEON might be preferred.</p>

<h3>General Usability and Mobile-Friendliness</h3>
<p>The advantages that AEON has over Monero are in the area of being lightweight and mobile friendly.  AEON has chosen a different Proof-of-Work algorithm which requires half the CPU cache memory and allows for faster verification of the blockchain. This decision sacrifices a bit of ASIC resistance for the sake of being mobile friendly.</p> 

<p>AEON's default number of "decoy" transaction signatures is 2 per transaction, while Monero's is 10.  AEON also allows the option for a limited number of fast, low-fee transfers with 0 decoys (which are traceable on the blockchain). These can be used for non-sensitive payments.  Monero, on the other hand, requires all payments to be fully anonymized. The result is that Monero's greater number of decoys on the blockchain adds to the validation times and blockchain size when compared to AEON. Thus, AEON sacrifices a bit of being untraceable for the sake of being lightweigt and mobile friendly.</p>

<p><b>NOTE:</b> The AEON community is considering elimination of the 0-decoy transactions, and raising the default number of decoys.  The popular default value suggestions seem to be 5 or 7 decoys, which would improve untraceability, while keeping the transaction sizes smaller than Monero's.</p>

<p>These aspects put AEON in a better position to be the secure, private currency that can be used by the general public with cell phones and tablets on the go.</p>

<h2>vs. Dash</h2>
<p>Dash stands for “digital cash" and is meant to work like physical cash when purchasing items online or in stores.  Like AEON, Dash embraces the importance of Security and Privacy.  There are some disadvantages, however, when comparing this coin to AEON.</p>

<h3>General Usability and Transactions-Per-Second</h3>
<p>In November, 2017, the Dash blockchain hard-forked to double it's maximum blocksize, to 2 MB. That change allowed Dash to process roughly 48 transactions per second.  As we have seen, this does not compare to credit card processors which typically see thousands of transactions per second.  At some point the Dash TPS must be increased again, and likely again after that.  This continued increasing of TPS via disruptive blockchain modifications is not conducive to massive adoption.</p>

<p>See section <i>vs. Bitcoin</i> for a description of AEON's solution to the TPS limitation.</p>

<h3>Mining, Governance and Barriers to Participation</h3>
<p>Dash uses a Proof-of-Work algorithm which is dependent primarily on CPU power, and the network welcomes the use of specialized hardware for mining. This has driven the hashrate high enough that currently only ASIC hardware mining is profitable.  The result is that the average person with a PC cannot readily participate in the transaction validation process of mining.</p>

<p>Additionally, Dash implements a complex form of Governance consisting of a 2nd tier network node, called a Masternode. In order to own a Masternode, one must obtain and hold 1000 Dash.  (In early 2019, this was an investment of roughly $80,000 USD.)  Only Masternode owners vote on proposed enhancements to the coin, as well as prioritize which projects get paid from the development fund.  Similar to AEON, new coins are disbursed as a block reward when a miner successfully validates a block of transactions.  But unlike AEON, the miner must split the block reward between the Masternodes and the Development Fund.</p>

<p>Because special hardware is required to mine Dash, and a large monetary investment is necessary to participate in the governance of the currency, the barriers to participation are much higher than with AEON's simple open source project model.  Even to submit a proposal for a vote by the Masternode owners, costs a fee of 5 Dash (roughly $400 USD in early 2019).  These factors work against a true decentralization for a currency.</p>

<p>AEON uses the traditional Open Source Model of participation and governance, which has been shown to work well for many large technology efforts for many years. It allows a diverse community to grow organically, which is an advantage for AEON's plans to become widely used by all walks of life.</p>

<h2>vs. Zcash</h2>
<p>Zcash is another fork of the Bitcoin code base, with the intent of adding the element of privacy to the blockchain.</p>

<h3>Privacy and Shielded Transactions</h3>
<p>Zcash achieves privacy by using a cryptographic approach called “zero-knowledge cryptography" to create “shielded transactions".  However, this is not the default option, and there is no limit to the number of non-private transactions in each block.  A recent report by ICO research firm Satis Group (“Cryptoasset Market Coverage Initiation: Valuation", August 30, 2018) states:</p>
 
<p>“Only ~5%  of the Zcash network uses 'shielded' addresses currently, with the rest of the addresses being used for transactions functionally and technically no different than Bitcoin."</p>

<p>The paper concludes that since there are so many more addresses in the blockchain that are not private, the Zcash network as a whole is not fungible.  Meaning the coins in any given wallet could possibly be traced back to their prior transactions.  (This is important, because nobody wants to find out that the coins in their wallet were used previously to commit a crime, etc.)</p>

<p>In contrast, the research states specifically that Monero -- and therefore we can conclude AEON as well -- is a fungible network.  Both Monero and AEON default to a private transaction, and AEON only allows at most 10% of the transactions in any block to be switched to non-private.</p>

<h3>Mining and Barriers to Participation</h3>
<p>Zcash went away from the Bitcoin PoW algorithm, and implemented the Equihash PoW algorithm, to provide ASIC resistance, and allow people to mine with their GPU’s and CPU’s.  The problems with the Equihash algorithm are that 1) it does not limit the advantage of GPU over CPU, and 2) ASICs were developed which could mine Zcash, threatening the future viability of GPU and CPU mining. In June of 2018, members of the Zcash community voted to not put resources toward developing resistance back into the Zcash PoW.</p>

<p>AEON's PoW, as stated previously, is more CPU friendly, and more ASIC resistant.  In addition, when an ASIC was successfully developed for the CryptoNight-Lite algorithm, the AEON developers quickly moved to fork the blockchain to regain ASIC resistance.</p>

<h3>General Usability and Transactions-Per-Second</h3>
<p>Zcash improved upon Bitcoin by doubling the maximum block size to 2 MB, and decreasing the block interval down to 2.5 minutes.  However the transaction size is larger in Zcash, so the maximum TPS will only reach about 26, and could be far less if more of the transactions happen to be shielded.  As with Bitcoin, the TPS throughput will need to be increased into the thousands before Zcash will become a currency used by the masses.</p>

<p>See section <i>vs. Bitcoin</i> for a description of AEON’s solution to the TPS limitation.</p>

<h2>vs. Ripple</h2>
<p>Of all the currencies discussed in this section, Ripple is one which may not belong.  The Ripple blockchain is open source, but Ripple is also a private company.  From their homepage:  “Ripple connects banks, payment providers, digital asset exchanges and corporates via RippleNet to provide one frictionless experience to send money globally."</p>

<p>Consider the ways in which Ripple's vision is different from AEON:</p>

*   Ripple does not decentralize the management of personal wealth; it seeks to strengthen the ability of central entities to control the movement of wealth on a global scale.
*   Working with banks, Ripple does not provide privacy, but instead provides full traceability of funds.
*   There is no mining process, by which individuals can receive coins for themselves.  All coins have been produced, and the Ripple company releases a certain number of coins per month.
