# Calculator
A calculator to perform basic arithmetic w/o taking input

//SPDX-License-Identifier:UNLICENSED

pragma solidity ^0.8.0;

contract calc{
    
    function add(uint a, uint b) public pure returns(uint) {
        return a+b;
    }

    function subtract(uint a, uint b) public pure returns(uint) {
        if (a>b){
        return a-b;
        }
        else 
        return b-a;
    }
        
    function multiply (uint a, uint b) public pure returns(uint){
        return a*b;
    }

    function divide(uint a, uint b) public pure returns(uint){
        if (a>b){
            return a/b;
        }
        else 
        return b/a;
    }

}
