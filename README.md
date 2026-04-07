# MessageStorage6.sol
MessageStorage6.sol6
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MessageStorage6 {
    string public message;
    function isEmpty() public view returns(bool){
        return bytes(message).length == 0;
    }
}
Implement owner access control
Remove redundant checks
Add event for tracking changes
