# l2pswap-lib

[![Tests](https://github.com/L2Protocol/l2pswap-solidity-lib/workflows/Tests/badge.svg)](https://github.com/L2Protocol/l2pswap-solidity-lib/actions?query=workflow%3ATests)
[![Static Analysis](https://github.com/L2Protocol/l2pswap-solidity-lib/workflows/Static%20Analysis/badge.svg)](https://github.com/L2Protocol/l2pswap-solidity-lib/actions?query=workflow%3A%22Static+Analysis%22)
[![Lint](https://github.com/L2Protocol/l2pswap-solidity-lib/workflows/Lint/badge.svg)](https://github.com/L2Protocol/l2pswap-solidity-lib/actions?query=workflow%3ALint)
[![Fuzz Testing](https://github.com/L2Protocol/l2pswap-solidity-lib/workflows/Fuzz%20Testing/badge.svg)](https://github.com/L2Protocol/l2pswap-solidity-lib/actions?query=workflow%3A%22Fuzz+Testing%22)
[![npm](https://img.shields.io/npm/v/@l2pswap/lib)](https://unpkg.com/@l2pswap/lib@latest/)

Solidity libraries that are shared across L2PSwap contracts. This package focuses on safety and execution gas efficiency.

## Install

Run `yarn` to install dependencies.

## Test

Run `yarn test` to execute the test suite.

## Usage

Install this in another project via `yarn add @l2pswap/lib`

Then import the contracts via:

```solidity
import '@l2pswap/lib/contracts/libraries/Babylonian.sol';

```
