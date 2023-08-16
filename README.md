# Flash Loans Testing

I have build an example where you can experience how we can start a flash loan. Note we won't be actually doing an arbitrage here, because finding profitable arbitrage opportunities is the hardest part and not related to the code, but will essentially learn how to execute a flash loan.

Try running some of the following tasks:

```shell
mkdir flash-loans
cd flash-loans
npm init --yes
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat
npm install @openzeppelin/contracts @aave/core-v3 dotenv
npx hardhat test
```
