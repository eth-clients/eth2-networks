# Nimbus

Please see the main repository of the Nimbus beacon chain for detailed instructions for building and running Nimbus:
https://github.com/status-im/nim-beacon-chain

Here is a short list of commands that can be used to connect to any of the testnets published here:

```bash
git clone https://github.com/status-im/nim-beacon-chain
cd nim-beacon-chain
make                 # This invocation will bootstrap the build system with additional Makefiles
make testnet0        # This will build Nimbus and all other dependencies
                     # and connect you to testnet0
```

Use `make testnet0` to rebuild and reconnect with an existing installation. 
`./connect-to-testnet testnet0` will also reset your testnet data to pristine state.
