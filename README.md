# ETH2 Testnets

This repository stores metadata files for the actively running Eth2 testnets in the period Q4/2019 - Q2/2020.

The folder structure and the contents of the files is described [here](https://github.com/ethereum/eth2.0-pm/blob/f1faca34b712b21602437b7627192cb9ba64edff/interop/deposit_contract_testnets/README.md).

### Single-Client Testnets

To connect to any of the published testnets using a particular client, please see the client-specific sub-folder for further instructions.

- [Lighthouse](lighthouse/):
    - [Testnet 0](lighthouse/testnet0/) (v0.9.2)
    - [Testnet 2](lighthouse/testnet2/)
    - [Testnet 5](lighthouse/testnet5/)
- [Nimbus](nimbus/)
    - [Testnet 0](nimbus/testnet0/) (v0.9.2)
    - [Testnet 1](nimbus/testnet1/) (v0.9.0)
- [Prysm](prysm/)
    - [Sapphire](prysm/Sapphire(v0.9.0)/) (v0.9.0)
    - [Sapphire](prysm/Sapphire(v0.9.4)/) (v0.9.4)
    - [Topaz](prysm/Topaz(v0.11.1)/) (v0.11.1)
    - [Onyx](prysm/Onyx(v0.12.1)/) (v0.12.1)

### Multi-Client Testnets

The following repositories contain client configurations for current and future multi-client testnets.

- [Schlesi Testnet](https://github.com/goerli/medalla/tree/master/.trash/schlesi/) (v0.11.2)
- [Witti Testnet](https://github.com/goerli/medalla/tree/master/witti) (v0.11.3)
- [Altona Testnet](https://github.com/goerli/medalla/tree/master/altona) (v0.12.1)
- [Medalla Testnet](https://github.com/goerli/medalla/blob/master/medalla) (v0.12.2)
- [Spadina Testnet](https://github.com/goerli/medalla/blob/master/spadina) (v0.12.3)

The multi-client interop scripts can be found at [eth2-clients/multinet](https://github.com/eth2-clients/multinet).

### Public Attacknets 

The following repositories contain public Eth2 attacknets with multiple tiers of bounties to incentivize breaking them.

- [Single-client `beta-0` attacknets](https://github.com/ethereum/public-attacknets/tree/master/attacknets/beta-0)
- [Multi-client `beta-1` attacknets](https://github.com/ethereum/public-attacknets/tree/master/attacknets/beta-1)
