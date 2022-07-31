# Liquid Staking Pallet
- Pallet interfaces with pallet-staking and pallet-democracy.

#### pallet-staking:
- New stakers can directly stake through your pallet, which controls all the staked dot, and generates a derivative token as well.
- Simple voting system in the pallet where holders of the derivative token can influence which validators the pallet backs.
- The derivative token is transferrable, hence “liquid” staking.
- Reward and slashing is accurate and reliable across this multi-pallet system.

#### pallet-democracy
- Users can vote on referenda using the tokens which are staked and managed by this pallet.

## Call
- stake(dot)
- unstake(ldot)
- claim_unstake(accountId) // anyone can do
- update_params()
