# yugho_decentralized_identity
A decentralized, trustless, identity management system with dispute support

This service will have the following features:
(1) Set up of a new Identity with public keys (key for account, key for each supported channel)
(2) Modification of existing account (change public keys, add/remove/modify channel)
(3) Recovery of Identity when channels are no longer valid
(4) Dispute Resolution of Identity when a party disputes who is the proper owner of the account
(5) Timeline of public keys including validation that a given public key was valid given a transaction id
(6) Subscription or transaction fee which can be used to sustain a decentralized identity management system for real.

The service depends on a message chain that uses a transaction id for each processed message  (the code in this service relies on yugho_message_chain for this)

The identity system can be used by a transaction system to provide a decentralized transaction system that does not depend on securing private keys.  For purposes of demonstrating this, I will be creating a repostory yugho_decentralized_transactions.  

This can also be used in line with a smart contract that enables an approval chain (approving part of the contract), a dispute chain (disputing a contract or the use of a contract for a subtransaction), and if used as a budget, discretionary chain.

The subscrpiton or transaction fee system will use the Spinoza Coin as the placeholder for any fee system which could be based on a decentralized currency or could be based on a trusted agent.

A decentralized system should work smoothly with the standard centralized systems. Ideally, consumers of this service can choose centralized or decentralized components as fits their needs.
