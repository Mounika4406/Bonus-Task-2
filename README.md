## How to Use
```solidity
// Check token balance
balanceOf(address) → uint256

// Transfer tokens
transfer(address to, uint256 amount) → bool

// Approve another wallet / DApp to spend your tokens
approve(address spender, uint256 amount) → bool

// Check approved spending limit
allowance(address owner, address spender) → uint256

// Transfer tokens on behalf of another (after approval)
transferFrom(address from, address to, uint256 amount) → bool
