![](https://i.imgur.com/QFZWlB8.png)

### See the presentation [here](https://docs.google.com/presentation/d/1UywBqI5BPFJGwuiuyk_dkiVG5Gp_MBcy3H9_N4azTIk/edit?usp=sharing)

## Backend Infrastructure

CryptoBonds is a blockchain application that was built using Hyperledger Sawtooth. The goal of the project is to make a stable coin with its value linked to real life company bonds. CryptoBonds acts as a clearing firm and monitors transactions between the banks and the traders. Traders are able to exchange cryptobonds and other cryptocurrencies with other users. 

## Prerequisits

All you need to run the backend of the code is docker. Once you've downloaded https://www.docker.com/products/docker-engine you need to enter these commands

```
git clone https://github.com/crypto-bonds/crypto-bonds
cd crypto-bonds/
docker-compose up
```

It will take about 20-30 minutes to compile the first time, but after the first time it will take less than a minute. Make sure you save the docker container.

This project was adapted from https://github.com/delventhalz/pirate-talk
