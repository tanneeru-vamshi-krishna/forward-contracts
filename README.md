# Forward Contracts

### Overview
Smart contracts to forward ETH to a pre-defined address.

### Requirements
- Contracts are pre-generated.
- Recipient's address is assigned in the constructor.
- Forwarding happens automatically and is in the same transaction of receiving ETH.
- Recipient can call other smart contracts via a proxy method. This is to recover ERC20 mistakenly sent to the Forward contract.
- Stateless.

### License
[GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.txt) &copy; WeTrustPlatform