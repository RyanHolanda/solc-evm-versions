# Default EVM version for each Solidity Compiler Version
This document outlines the default EVM (Ethereum Virtual Machine) version associated with each Solidity compiler version.

## Solidity >= 0.8.20 - Shanghai
### Important Note
With the Shanghai compiler, the default target EVM version includes PUSH0 opcodes. Ensure you select the appropriate EVM version for deployment, especially on non-mainnet chains like L2 chains that may not yet support PUSH0, to avoid deployment failures.

## Solidity >= 0.8.18 - Paris
## Solidity >= 0.8.7 - London
## Solidity >= 0.8.5 - Berlin
## Solidity >= 0.5.14 - Istanbul
## Solidity >= 0.5.5 - Petersburg
## Solidity >= 0.4.21 - Byzantium
### Important Note
You can now specify the EVM version for contract compilation. Valid values include "homestead", "tangerineWhistle", "spuriousDragon", "byzantium" (the default), and "constantinople".

# Source
For more information, refer to the [Solidity Changelog](https://github.com/ethereum/solidity/blob/develop/Changelog.md).

