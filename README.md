# Metacraft
Solidity
challange 1

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract SimpleContract {
    // Declare variables
    int256 private intValue;
    bool private boolValue;
    address private addressValue;
    string private stringValue;

    // Set and get functions for intValue
    function setIntValue(int256 _value) public returns (int256) {
        intValue = _value;
        return intValue;
    }

    function getIntValue() public view returns (int256) {
        return intValue;
    }

    // Set and get functions for boolValue
    function setBoolValue(bool _value) public returns (bool) {
        boolValue = _value;
        return boolValue;
    }

    function getBoolValue() public view returns (bool) {
        return boolValue;
    }

    // Set and get functions for addressValue
    function setAddressValue(address _value) public returns (address) {
        addressValue = _value;
        return addressValue;
    }

    function getAddressValue() public view returns (address) {
        return addressValue;
    }

    // Set and get functions for stringValue
    function setStringValue(string memory _value) public returns (string memory) {
        stringValue = _value;
        return stringValue;
    }

    function getStringValue() public view returns (string memory) {
        return stringValue;
    }
}


