# ConstructorExample.sol
ConstructorExample.sol
pragma solidity ^0.8.20;
contract ConstructorExample {
    uint public value;

    constructor(uint _value) {
        value = _value;
    }
}
