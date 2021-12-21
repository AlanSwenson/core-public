# Wolf Game Bug Bounty

This repository contains the code and scope definition for the Wolf Game bug bounty program.

## Bug Bounty

Wolf Gmae is offering up to $50,000 as a bounty for any vulnerabilities found. The amount received by the party that notifies me of a vulnerability will be determined based on severity.

Vulnerabilities should be submitted via this [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfWr5PxOq5NhFEG8jgPAG8IcTRDyj_X1M-RIwPNg8z6iBM3Kg/viewform) and the first submitter of any vulnerability will be eligible.

## Code For Review

The following smart contracts are currently in scope:

- Wool [Implementation](https://etherscan.io/address/0x8355dbe8b0e275abad27eb843f3eaf3fc855e525#code)
- WoolfReborn [Proxy](https://etherscan.io/address/0x7f36182dee28c45de6072a34d29855bae76dbe2f#code) [Implementation](https://etherscan.io/address/0x6aed9e5dda93b4243e87438790fea310fd182ea1#code) [Github](migration/WoolfReborn.sol)
- Wool Pouch [Proxy](https://etherscan.io/address/0xb76FBBB30e31F2c3BDaA2466CfB1CfE39b220D06#code) [Implementation](https://etherscan.io/address/0x45ef97f7995f7250bad0d1dc745d17cc5f508734#code) [Github](riskygame/WoolPouch.sol)
- Risky Game [Proxy](https://etherscan.io/address/0x830050A92e1694a2044dD1DDD1395E2CDadA8f2B) [Implementation](https://etherscan.io/address/0x867d1ef01122c87b1a5ee07effd06dc9c906f437#code) [Github](riskygame/RiskyGame.sol)

Bugs in legacy smart contracts such as Woolf v1 and Barn are not eligible for a bounty.


Happy Hunting,

The Shepherd & The Herdsman
