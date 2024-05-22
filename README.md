# ETH2 Networks

⚠️ This repository is no longer maintained - for the latest mainnet metadata, see https://github.com/eth-clients/mainnet

This repository stores metadata files for known [eth2 networks](https://github.com/ethereum/eth2.0-specs).

The folder structure and the contents of the files is described [here](https://github.com/ethereum/eth2.0-pm/blob/f1faca34b712b21602437b7627192cb9ba64edff/interop/deposit_contract_testnets/README.md).

### Mainnet

- [Mainnet](shared/mainnet) - The mainnet of the project formerly known as eth2

### Post-Launch Testnets

The following testnets were launched along with or after the public Ethereum 2.0 mainnet launch.

- [Pyrmont Testnet](shared/pyrmont) (v1.0.0)
- [Prater Testnet](shared/prater) (v1.0.1)

### Multi-Client Testnets (archive)

The following repositories contain client configurations for multi-client testnets.

- [Schlesi Testnet](https://github.com/goerli/medalla/tree/master/.trash/schlesi/) (v0.11.2)
- [Witti Testnet](https://github.com/goerli/medalla/tree/master/witti) (v0.11.3)
- [Altona Testnet](https://github.com/goerli/medalla/tree/master/altona) (v0.12.1)
- [Medalla Testnet](https://github.com/goerli/medalla/blob/master/medalla) (v0.12.2)
- [Spadina Testnet](https://github.com/goerli/medalla/blob/master/spadina) (v0.12.3)
- [Zinken Testnet](https://github.com/goerli/medalla/blob/master/zinken) (v0.12.3)
- [Toledo Testnet](shared/toledo/) (v1.0.0)

The multi-client interop scripts can be found at [eth-clients/multinet](https://github.com/eth-clients/multinet).

The differential beacon-chain fuzzing framework can be found at [sigp/beacon-fuzz](https://github.com/sigp/beacon-fuzz).

### Public Attacknets (archive)

The following repositories contain public Eth2 attacknets with multiple tiers of bounties to incentivize breaking them.

- [Single-client `beta-0` attacknets](https://github.com/ethereum/public-attacknets/tree/master/attacknets/beta-0)
- [Multi-client `beta-1` attacknets](https://github.com/ethereum/public-attacknets/tree/master/attacknets/beta-1)

### Single-Client Testnets (archive)

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
- [Teku](teku/)
    - [Coorparoo](teku/coorparoo/) (Altair)

