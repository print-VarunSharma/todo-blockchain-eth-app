# TODO Smart Contract App

## Summary

Create & Deploy a simple TODO list app to the blockchain!

## Project Dependencies

1. https://trufflesuite.com/ganache/
2. https://metamask.io
3. https://trufflesuite.com

## Installation

### Dev Installation

1. npm i

2. Truffle init

3. truffle compile

4. Ensure that the PORT in the truffle-config.js matches Ganache's PORT for local development

5. Truffle migration

6. Deploying Smart Contracts to the Blockchain costs ETH (gas). So once migration is done, truffle should have decreased ETH

7. truffle console

8. Test Smart contract commands with these:
   todoList = await TodoList.deployed()
   todoList.address
   taskCount = await todoList.taskCount()
   taskCount.toNumber()
