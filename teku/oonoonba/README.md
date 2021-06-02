# Oonoonba Altair Devnet
Oonoonba is a short-lived Devnet that activates the Altair fork at epoch 10. It's based on the v1.1.0-alpha.6 spec.
The new preset based config is used in `config.yaml` based on the mainnet preset.  Old style config is available in `phase0.yaml` and `altair.yaml`.

To run you'll need a `develop` version of Teku.

From in this directory, Teku can join Oonoonba with:

```shell
teku --network config.yaml \
     --Xnetwork-altair-fork-epoch 10 \
     --initial-state genesis.ssz \
     --p2p-discovery-bootnodes "enr:-KG4QLXhcaTSEqPF-g5T_t-7NJJ6DQTHy8yCV-vvjJHU7jwOUpGMdIcvlKB4roS9qG1mi-P38Pvq1GkHYblRpOvfi6UDhGV0aDKQk_tI4gEASBEKAAAAAAAAAIJpZIJ2NIJpcIQS2MfriXNlY3AyNTZrMaECmgO9ATicNnBAl0Z1wKtbfvVlxv70aiJ7Obx_bFyhGpeDdGNwgiMog3VkcIIjKA,enr:-KG4QKHoILkdRrVT253n_S_cWB9K27hKGfQBUjT7Vw_dpTj2Y7BtIcEshnlj4fERg9IDer8CzwLjpCM809ZJ0Qym7dMDhGV0aDKQk_tI4gEASBEKAAAAAAAAAIJpZIJ2NIJpcIQS3pANiXNlY3AyNTZrMaED-iX-fx0c0RglNfwWG7N-K3oI-3JXM2O0Nyd67D5U1raDdGNwgiMog3VkcIIjKA"
```