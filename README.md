# Flok Test (FLT) Token

## Overview

The Flok Test (FLT) token is an ERC-20 compliant token on the Ethereum blockchain. It represents a test token for the Flok project. This contract provides basic functionality for managing and transferring tokens.

## Token Details

- Name: Flok Test
- Symbol: FLT
- Decimals: 18
- Total Supply: 21,000,000 FLT

## Functions

### name

```solidity
function name() public view returns (string memory)
```

Returns the name of the token.

### symbol

```solidity
function symbol() public view returns (string memory)
```

Returns the symbol of the token.

### decimals

```solidity
function decimals() public view returns (uint8)
```

Returns the number of decimal places used for token representation.

### totalSupply

```solidity
function totalSupply() public view returns (uint256)
```

Returns the total supply of tokens.

### balanceOf

```solidity
function balanceOf(address account) public view returns (uint256)
```

Returns the token balance of the specified account.

### transfer

```solidity
function transfer(address to, uint256 amount) public returns (bool)
```

Transfers a specified amount of tokens from the caller's account to the specified recipient. Returns a boolean value indicating the success of the transfer.

### allowance

```solidity
function allowance(address owner, address spender) public view returns (uint256)
```

Returns the current allowance granted to the spender by the owner.

### approve

```solidity
function approve(address spender, uint256 amount) public returns (bool)
```

Sets an allowance for the spender to spend a specified amount of tokens on behalf of the caller.

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 amount) public returns (bool)
```

Transfers a specified amount of tokens from the `from` address to the `to` address using the allowance mechanism. Requires approval from the `from` address.

### increaseAllowance

```solidity
function increaseAllowance(address spender, uint256 addedValue) public returns (bool)
```

Atomically increases the allowance granted to the spender by the caller.

### decreaseAllowance

```solidity
function decreaseAllowance(address spender, uint256 subtractedValue) public returns (bool)
```

Atomically decreases the allowance granted to the spender by the caller.

### burn

```solidity
function burn(uint256 amount) public virtual
```

Destroys a specified amount of tokens from the caller's account.

### burnFrom

```solidity
function burnFrom(address account, uint256 amount) public virtual
```

Destroys a specified amount of tokens from the specified account, deducting from the caller's allowance.

---

Please note that this description page assumes basic knowledge of ERC-20 tokens and their functionalities. 
It provides an overview of the token's features and the available functions for investors and users to interact with the Flok Test token.
