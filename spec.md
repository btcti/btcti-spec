#            bitcoin-ti     feature    set


## X11 


X11 is a widely used hashing algorithm created by Dash core developer Evan Duffield. X11’s chained hashing algorithm utilizes a sequence of eleven scientific hashing algorithms for the proof-of-work. This is so that the processing distribution is fair and coins will be distributed in much the same way Bitcoin’s were originally. X11 was intended to make ASICs much more difficult to create, thus giving the currency plenty of time to develop before mining centralization became a threat. This approach was largely successful; as of early 2016, ASICs for X11 now exist and comprise a significant portion of the network hashrate, but have not resulted in the level of centralization present in Bitcoin.

X11 is the name of the chained proof-of-work (PoW) algorithm that was introduced in Dash (launched January 2014 as “Xcoin”). It was partially inspired by the chained-hashing approach of Quark, adding further “depth” and complexity by increasing the number of hashes, yet it differs from Quark in that the rounds of hashes are determined a priori instead of having some hashes being randomly picked.

The X11 algorithm uses multiple rounds of 11 different hashes (blake, bmw, groestl, jh, keccak, skein, luffa, cubehash, shavite, simd, echo), thus making it one of the safest and more sophisticated cryptographic hashes in use by modern cryptocurrencies.


## Advantages of X11

The increased complexity and sophistication of the chained algorithm provides enhanced levels of security and less uncertainty for a digital currency, compared to single-hash PoW solutions that are not protected against security risks like SPOF (Single Point Of Failure). For example, a possible but not probable computing breakthrough that “breaks” the SHA256 hash could jeopardize the entire Bitcoin network until the network shifts through a hard fork to another cryptographic hash.

In the event of a similar computing breakthrough, a digital currency using the X11 PoW would continue to function securely unless all 11 hashes were broken simultaneously. Even if some of the 11 hashes were to prove unreliable, there would be adequate warning for a currency using X11 to take measures and replace the problematic hashes with other more reliable hashing algorithms.

Given the speculative nature of digital currencies and their inherent uncertainties as a new field, the X11 algorithm can provide increased confidence for its users and potential investors that single-hash approaches cannot. Chained hashing solutions, like X11, provide increased safety and longevity for store of wealth purposes, investment diversification and hedging against risks associated with single-hash currencies plagued by SPOF (Single Point Of Failure).

Evan Duffield, the creator of Dash and X11 chained-hash, has wrote on several occasions that X11 was integrated into Dash not with the intention to prevent ASIC manufacturers from creating ASICs for X11 in the future, but rather to provide a similar migratory path that Bitcoin had (CPUs, GPUs, ASICs).



##   Dark Gravity Wave


**DGW**  or Dark Gravity Wave is an open source difficulty-adjusting algorithm for Bitcoin-based cryptocurrencies that was first used in Darkcoin/Dash and has been adopted by other digital currencies.

**DGW** was authored by Evan Duffield, the developer and creator of X11/Darkcoin/Dash, as a response to a time-warp exploit found in Kimoto's Gravity Well. 

In concept, **DGW** is similar to Kimoto Gravity Well, adjusting the difficulty levels every block (instead of every 2016 blocks like Bitcoin) by using statistical data of the last blocks found. In this way block issuing times can remain consistent, despite high fluctuations in hashpower. However it doesn't suffer from the time-warp exploit. 

Version 2.0 of **DGW** was implemented in Darkcoin/Dash from block 45.000 onwards in order to completely alleviate the time-warp exploit. 

Version 3.0 was implemented on May 14 of 2014 to further improve difficulty re-targeting with smoother transitions. It also fixes issues with various architectures that had different levels of floating-point accuracy through the use of integers.