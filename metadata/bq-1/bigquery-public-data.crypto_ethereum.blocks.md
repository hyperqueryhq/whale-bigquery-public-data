# `crypto_ethereum.blocks`
`bq-1` | `bigquery-public-data`
The Ethereum blockchain is composed of a series of blocks. This table contains a set of all blocks in the blockchain and their attributes.
Data is exported using https://github.com/medvedev1088/ethereum-etl

## Column details
* [TIMESTAMP] `timestamp`
  - The timestamp for when the block was collated
* [INTEGER]   `number`
  - The block number
* [STRING]    `hash`
  - Hash of the block
* [STRING]    `parent_hash`
  - Hash of the parent block
* [STRING]    `nonce`
  - Hash of the generated proof-of-work
* [STRING]    `sha3_uncles`
  - SHA3 of the uncles data in the block
* [STRING]    `logs_bloom`
  - The bloom filter for the logs of the block
* [STRING]    `transactions_root`
  - The root of the transaction trie of the block
* [STRING]    `state_root`
  - The root of the final state trie of the block
* [STRING]    `receipts_root`
  - The root of the receipts trie of the block
* [STRING]    `miner`
  - The address of the beneficiary to whom the mining rewards were given
* [NUMERIC]   `difficulty`
  - Integer of the difficulty for this block
* [NUMERIC]   `total_difficulty`
  - Integer of the total difficulty of the chain until this block
* [INTEGER]   `size`
  - The size of this block in bytes
* [STRING]    `extra_data`
  - The extra data field of this block
* [INTEGER]   `gas_limit`
  - The maximum gas allowed in this block
* [INTEGER]   `gas_used`
  - The total used gas by all transactions in this block
* [INTEGER]   `transaction_count`
  - The number of transactions in the block
* [INTEGER]   `base_fee_per_gas`
  - Protocol base fee per gas, which can move up or down
* [STRING]    `withdrawals_root`
  - The root of the withdrawal trie of the block
* [RECORD]    `withdrawals`
  - Validator withdrawals
* [INTEGER]   `withdrawals.index`
* [INTEGER]   `withdrawals.validator_index`
* [STRING]    `withdrawals.address`
* [STRING]    `withdrawals.amount`
* [INTEGER]   `blob_gas_used`
  - The total amount of blob gas consumed by transactions in the block
* [INTEGER]   `excess_blob_gas`
  - A running total of blob gas consumed in excess of the target, prior to the block. This is used to set blob gas pricing

-------------------------------------------------------------------------------
*Do not make edits above this line.*
