# Eth2.0 Mainnet

To learn more about Eth2.0, refer to the [Eth2.0 specifications](https://github.com/ethereum/eth2.0-specs).

*This repository is primarily a resource for developers, to share things which are not directly part of the specification,
 but rather some type of metadata or product of running the specification.*

## Genesis information

```yaml
genesis_time: 1606824023
genesis_state_root: 0x7e76880eb67bbdc86250aa578958e9d0675e64e714337855204fb5abaaf82c2b
genesis_block_root: 0xeade62f0457b2fdf48e7d3fc4b60736688286be7c7a3ac4c9a16a5e0600bd9e4
genesis_validators_root: 0x4b363db94e286120d76eb905340fdd4e54bfe9f06bf33ff6cf5ad27f511bfe95
genesis_validators_count: 21063
genesis_active_validators_count: 21063
genesis_total_active_stake_gwei: 674016000000000
genesis_total_balance_gwei: 674144000000000
eth1_data:
  deposit_root: 0x1a4c3cce02935defd159e4e207890ae26a325bf03e205c9ee94ca040ecce008a
  deposit_count: 21073
  block_hash: 0xeeea1373d4aa9e099d7c9deddb694db9aeb4577755ef83f9b6345ce4357d9abf
genesis_fork_version: 0x00000000
genesis_fork_digest: 0xb5303f2a
pre_genesis_fork_digest: 0xf5a5fd42
```

Above can be verified with a `genesis.ssz` and then running `compute_genesis_details.py`


## License

CC0 1.0 Universal. See [`LICENSE`](./LICENSE).
