# Prysm

For detailed information on how to set up and run our beacon and validator nodes, that can be found
over [here](https://github.com/prysmaticlabs/prysm). 

The easiest way to run our beacon nodes and validators for our current Sapphire testnet would be through docker:

Download docker images for both beacon and validator client  
```bash
docker pull gcr.io/prysmaticlabs/prysm/beacon-chain:latest
docker pull gcr.io/prysmaticlabs/prysm/validator:latest
```

Then run beacon node and validator client
```bash
docker run -v $HOME/prysm-data:/data -p 4000:4000 \
  --name beacon-node \
  gcr.io/prysmaticlabs/prysm/beacon-chain:latest \
  --no-genesis-delay \
  --datadir=/data
  
docker run -it -v /usr/local/prysm/validator:/data \
     gcr.io/prysmaticlabs/prysm/validator:latest \
     accounts create --keystore-path=/data --password=changeme

```