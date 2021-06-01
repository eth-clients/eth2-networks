# Altair Devnet
Coorparoo is a short-lived Devnet that activates the Altair fork at epoch 10. It's based on the v1.1.0-alpha.6 spec 
but the supplied config is still in the older 2 file format rather than using split preset & configuration.

To run you'll need a `develop` version of Teku (or probably `v21.6.0` should work when released).

From in this directory, Teku can join Coorparoo with:

```shell
teku --network ./ \
     --Xnetwork-altair-fork-epoch 10 \
     --initial-state genesis.ssz \
     --p2p-discovery-bootnodes "enr:-KG4QGtLfpaTMJKBD8_VTE0ZBf24KoVrnT-Toc5K6IuQwUm2WQShEmmjEwZc1B3J3muXaDoIYt3Qty9xEFCdvKeOq1sDhGV0aDKQFmWbwwAAQVH__________4JpZIJ2NIJpcIQS2MfriXNlY3AyNTZrMaEC0y6UqTmdr_Jw_4L_bi1Tlp9i-WT5T8MKHs0r77RUonqDdGNwgiMog3VkcIIjKA,enr:-KG4QOWkRj93eXbzMLc6Jvps6lXzlIq6CFmYQJV93QtkglAUf6C2myzSU8Zzay1iYxvQp0w3FD5XLQnitMtIIEwhJwgDhGV0aDKQFmWbwwAAQVH__________4JpZIJ2NIJpcIQS3pANiXNlY3AyNTZrMaEC5Z9hdyMHa64JhYZFVf40uI9BnzKWd2Y_NNG9sUcs0gWDdGNwgiMog3VkcIIjKA"
```