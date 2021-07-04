# Identity Buyer

This repository holds everything you need to buy and see an IdentiTree CO2 Certificate.


## Setup the wallet.

1. Init the wallet and store the seed somewhere.
```bash
./cli-wallet init
```

2. Get your revieve address
```bash
./cli-wallet address -receive
```

3. Check the balance
```bash
./cli-wallet balance
```
4. Buy a certificate
Go to the market and run the [application](https://github.com/IdentiTree/market). Create an Certificate by adding your DID and your address.
The creating and mint prozess could take a while (about 1 minute).

5. Check your new balance