# Tokens.mligo

Tokens is a tezos smart contract that allows people create thier own fungible (erc20) fa2 standard tokens. All the management is done in one smart contract and all the fa2 operations are supported.

Current Features
1. you can create your own token with the details on chain
2. Each token that is created has a fixed supply that is instantiated when the entrypoint is called
3. The owner of the token can mint out coins from the available supply to addresses

Ways the contract could be improved
1. allow option for a dao contract to own a token
2. allow multi people have ownership of a token
3. be able to transfer ownership


The contract is deployed on the granada testnet, here https://better-call.dev/granadanet/KT1KfYaJYPAJaVtrJsrzR8y1BXcmvCEGzJ8W/storage
