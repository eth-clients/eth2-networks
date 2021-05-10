![](nocturne.jpg)

"Nocturne". Photo credit: © ADAGP, Paris and DACS, London 2020

# Nocturne

Nocturne, named after the [rayonist painting](https://www.tate.org.uk/art/artworks/larionov-nocturne-n06192),
is the final Merge devnet of the [Rayonism](https://rayonism.io) project during the hackathon phase.

It generally follows the Rayonism spec, which is Eth1 up to and incl. Berlin, Eth2 phase0 with Merge extension (i.e. no Altair fork yet), and is configured with mainnet-like settings.

Config files:
- [eth1 config (geth format)](https://github.com/protolambda/nocturne/blob/master/eth1_config.json)
- [eth1 config (nethermind/open-ethereum format)](https://github.com/protolambda/nocturne/blob/master/eth1_nethermind_config.json)
- [eth2 config](https://github.com/protolambda/nocturne/blob/master/eth2_config.yaml)
- [Discv5 bootnodes](https://github.com/protolambda/nocturne/blob/master/bootnodes.txt)

Assets:
- [`genesis.ssz`](./genesis.ssz)

Data:

```yaml
genesis_time: 1620820800   # 2021-05-12 12:00:00 UTC
genesis_state_root: 0x882503fe00df9b5044404d6c6f07b991b5f9795c28de9dcfb049ecc3a5f887b6
genesis_block_root_with_zero_state_root: 0xb8db6776f4a1a27f92688298fbdd98161999e9d726324affae423b7a21e6dca4
genesis_block_root_with_good_state_root: 0x40c717968b2ebe859df24379311235fcde11d8c7090ca29beb7ecc8f5ab058cb
genesis_validators_root: 0x61304c66f10a5c51261d474920b88111c29d378b72fa8d35b3dec5919f7d6ff6
genesis_validators_count: 20200
genesis_active_validators_count: 20200
genesis_total_active_stake_gwei: 646400000000000
genesis_total_balance_gwei: 646400000000000
eth1_data:
  deposit_root: 0xd70a234731285c6804c2a4f56711ddb8c82c99740f207854891028af34e27e5e
  deposit_count: 0
  block_hash: 0xf936f4395596714b84f731c2aec62047547c77fecc786b71ce587c628f0e51a4
eth1_chain_id: 702
deposit_contract_address: 0x4242424242424242424242424242424242424242
genesis_fork_version: 0x00000702
genesis_fork_digest: 0xe8fa8867
pre_genesis_fork_digest: 0x84a8272e
execution_payload:
  block_hash: 0xf936f4395596714b84f731c2aec62047547c77fecc786b71ce587c628f0e51a4
  parent_hash: 0x0000000000000000000000000000000000000000000000000000000000000000
  coinbase: 0x0000000000000000000000000000000000000000
  state_root: 0xc129ce6b9e4d93c9e48f4919157cb2cd2d1d08826c0ed5f7efb65d1fb1a6526c
  number: 0
  gas_limit: 4194304
  gas_used: 0
  timestamp: 1620820800   # 2021-05-12 12:00:00 UTC
  receipt_root: 0x56e81f171bcc55a6ff8345e692c0f86e5b48e01b996cadc001622fb5e363b421
  logs_bloom: 0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
  transactions_root: 0xe05ac02c0a8f889909fdb5ff44a8267e088b0e7eb6c11bbea096023884da27b8
```
