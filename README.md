# liquidity-lock
This is a contract that locks the liquidity pool tokens.

## Instructions

The owner has to specify the address of the LPAddress variable to his LP tokens address.

When deploying the contract the owner has to specify the days of locked time, so entering the number 5 would mean that the tokens would be locked for 5 days after deployement.

Lock time can also be increased by calling the addMoreDays function with input the number of days the owner is willing to add.

If the LP address is wrong the owner can change it by calling the SetLPAddress function with the correct address.

After deploying the contract the owner will have to send the LP tokens to the contract's address, he will only be able to withdraw after the lock time has passed.
