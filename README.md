# evm client

This is an embedded standalone Ethereum EVM and ledger running
within a Java process.
Everything runs within the JVM process, including EVM bytecode, which
allows for easy debugging of Solidity smart contracts. There is no need to start up
external Geth nodes.

Checkout [web3j-unit](https://github.com/web3j/web3j-unit)
project. You can use it to run unit and integration tests without the need
to start an Ethereum node.

A demo is available on the [example project](./evm-example).

One can do ETH transactions, contract deployment and simple contract interactions. 
Using the ConsoleDebugTracer, you can step through the EVM bytecode, inspect the stack and also see
where in the solidity code being executed.
The demo shows how to use `EmbeddedWeb3jService`.

Check more details at [web3j project] https://github.com/web3j/

# Fantom's opera client

TODO