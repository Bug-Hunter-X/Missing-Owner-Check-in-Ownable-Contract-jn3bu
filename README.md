This repository contains a Solidity smart contract demonstrating a common bug in DApps. The contract is supposed to be an ownable contract, where only the owner can transfer ownership. However, it's vulnerable because it doesn't verify the caller's identity, making it possible for attackers to transfer ownership without authorization.