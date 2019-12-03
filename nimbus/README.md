# Nimbus

Please see the main repository of the Nimbus beacon chain for detailed instructions for building and running Nimbus:
https://github.com/status-im/nim-beacon-chain

Here is a short list of commands that can be used to connect to any of the testnets published here:

```bash
git clone https://github.com/status-im/nim-beacon-chain
cd nim-beacon-chain
make                 # This invocation will bootstrap the build system with additional Makefiles
make update deps     # This will build Nim and all other dependencies
./connect-to-testnet testnet0
```

