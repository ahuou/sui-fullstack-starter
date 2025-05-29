## Move Smart contract

In this part, you will be able to write and deploy your smart contract. 

You are greatly incouraged to test your smart contracts through the making of tests in the appropriate folder although interacting with your smart contract is another good yet less rigourous way of testing your code. 

### Install Sui CLI 

Before creating your smart contracts, you must install the sui CLI. To check if you have it installed run 
```bash
sui --version
```
If you don't have it installed you may follow [this tutorial.](https://docs.sui.io/guides/developer/getting-started/sui-install)

### Creating new move package

If for some reason you desire to create another move package you may do so using 

```bash
sui move new <project-name>
```