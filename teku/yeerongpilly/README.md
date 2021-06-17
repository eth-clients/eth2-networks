# Yeerongpilly Altair Devnet
Yeerongpilly is a short-lived Devnet that activates the Altair fork at epoch 20. It's based on the v1.1.0-alpha.7 spec.
The new preset based config is used in `config.yaml` based on the mainnet preset.  Old style config is available in `phase0.yaml` and `altair.yaml`.

To run you'll need a `develop` version of Teku.

From in this directory, Teku can join Yeerongpilly with:

```shell
teku --network config.yaml \
     --Xnetwork-altair-fork-epoch 20 \
     --initial-state genesis.ssz \
     --p2p-discovery-bootnodes ""
```