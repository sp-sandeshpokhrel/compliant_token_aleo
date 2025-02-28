
## Compliance Rule: Claiming Funds Restriction
To enforce fair fund withdrawals, users can only claim funds **once per hour**. This is implemented by checking the **block height difference** when invoking the `get_funds` function. If a user attempts to claim funds again within one hour (based on the block height), the transaction will fail.

