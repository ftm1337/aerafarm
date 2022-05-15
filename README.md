# aerafarm
## What
MasterChef for Aerarium Finance, $AERA. On Metis Andromeda.

## How
### Construction 
 ```
 {
   address aera,
   address _treasuryAddress,
   uint256 _aeraPerBlock,
   uint256 _startBlock
 }
 ```
### Initialization
- Send AERA Tokens to this address
- `add()` new pools

### End-user Usage
- Users can now deposit and farm.

### Secondary Rewards
- `set()` parameters to existing pool with `rewarder` contract
