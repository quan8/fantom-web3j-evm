# evm client

This is an embedded standalone Ethereum EVM and ledger running
within a Java process. Everything runs within the JVM process, including EVM bytecode, which
allows for easy debugging of Solidity smart contracts.

With [web3j-unit](https://github.com/web3j/web3j-unit)
project, you canrun unit and integration tests without the need
to start an Ethereum node.