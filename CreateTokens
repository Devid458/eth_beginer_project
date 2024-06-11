pragma solidity 0.8.18;

contract GetToken {
    string public name = "GetTokens";
    string public symbol = "Gttkns";
    uint public totalsupply;
mapping(address => uint) public balances;

function mint(address _to, uint _amount) public{
      totalsupply += _amount;
      balances[_to]+= _amount;
}

function burn(address _address, uint _amount) public{
    if (balances[_address] >= _amount){
        totalsupply = _amount;
        balances[_address]= _amount;
    }
}
}
