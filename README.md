# WalletInfo.sol
How to deploy a contract on Base Chain WalletInfo.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract WalletInfo {
    function getSender() public view returns (address) {
        return msg.sender;
    }

    function getValue() public payable returns (uint) {
        return msg.value;
    }
}
