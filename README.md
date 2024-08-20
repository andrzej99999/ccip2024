Day 2 Homework ccip 2024


Create an instance of CCIPLocalSimulator.sol smart contract.

Call the configuration() function to get Router contract address.

Create instances of CrossChainNameServiceRegister.sol, CrossChainNameServiceReceiver.sol and CrossChainNameServiceLookup.sol smart contracts and call the enableChain() function where needed.

Call the setCrossChainNameServiceAddress function of the CrossChainNameServiceLookup.sol smart contract "source" instance and provide the address of the CrossChainNameServiceRegister.sol smart contract instance. Repeat the process for the CrossChainNameServiceLookup.sol smart contract "receiver" instance and provide the address of the CrossChainNameServiceReceiver.sol smart contract instance. 

Call the register() function and provide “alice.ccns” and Alice’s EOA address as function arguments.

Call the lookup() function and provide “alice.ccns” as a function argument. Assert that the returned address is Alice’s EOA address.

Send a url pointing to the public Github repository.
