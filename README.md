# An NFT Collection Contract

**Built as part of my learnweb3Dao tutorial**

- Here two contract addresses are involed. (the second is the main contract)
  _The first contract is used as an interface to check if addresses calling the second contract had been whitelisted_

- if an address calling the presale mint function had been whitelisted in the interface contract, then it is eligible to mint during the presale blocktimestamp, if not, the address will have to wait for the presale to end before minting.
- The main contract also has a maximun number of NFTs to be minted and once this number is exceeded, minting stops.
- The cost of minting each NFT is 0.01 Ether.
