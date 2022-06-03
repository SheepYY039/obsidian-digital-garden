---
{"dg-publish":true,"permalink":"/61-archive/20220405201201-smart-contract-file-types/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Smart Contract File Types

## Contract

- Normal [Smart Contract](20220327121426%20Smart%20Contract.md)
- All functions have been implemented

## Abstrack Contract

- When not all contracts within a file has been deployed

## Interface

- Only function declarations
- Name Always start with `I`
  - `interface IMyContract {}`
- No function implementations
- No state variables, modifiers, constructors
- Can inherit other interfaces
- Cannot inherit from other contracts
- Like `typescript` type files

## Library

- Just like <mark class="hltr-red">tool box </mark>
- No state variables, only functions
- Cannot inherit and be inherited
- Cannot receive ether
- Types
  - `internal`/ `private`
  - `public`
  - Lies on the [ethereum](20220327120946-ethereum.md) blockchain
  - Deployed by others
