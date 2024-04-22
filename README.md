## SOLIDITY FUNCTIONS
Getting Started with Solidity. The project is to create a functions. 
## Description

In this project I create a solidity contract with 4 functions; add, subtract, multiply and divide 2 numbers.
## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are in the compiler. Copy and paste the following code: 

```javascript
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.7;

contract Functions {
function add (uint x, uint y) external pure returns (uint) {
        return x + y;
    }
    function subtract (uint x, uint y) external pure returns (uint) {
        return  x - y;
    }
    function multiply (uint x, uint y) external pure returns (uint) {
        return x * y;
    }
    function divide (uint x, uint y) external pure returns (uint) {
        require(y != 0, "Division by zero is not allowed");
        return  x / y;
    }
}
```
## Authors

Contributors names and contact info



## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
