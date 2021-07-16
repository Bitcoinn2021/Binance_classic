# Binance_classic

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol";

contract Binance_classic is ERC20 {
    constructor(uint256 initialsupply) public ERC20 ("Binance_classic", "BNBC") {
        _mint(msg.sender,initialsupply);
         }
         
