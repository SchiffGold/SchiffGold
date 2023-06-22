- 👋 Hi, I’m @SchiffGold
- 👀 I’m interested in ... Stocks
- 🌱 I’m currently learning ... Investor
- 💞️ I’m looking to collaborate on ... Network Systems
- 📫 How to reach me ... +(61)423 175 714

<!---
SchiffGold/SchiffGold is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Show ethereum/go-ethereum repo
## Daniel B Leahy: @SchiffGold

**app.tether.to**

Contract Security Audit
Callisto Network - July 10th, 2019 - Security Audit Report
Contract ABI
Export ABI
[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_upgradedAddress","type":"address"}],"name":"deprecate","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"_spender","type":"address"},{"name":"_value","type":"uint256"}],"name":"approve","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"deprecated","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_evilUser","type":"address"}],"name":"addBlackList","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_from","type":"address"},{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transferFrom","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"upgradedAddress","outputs":[{"name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"}],"name":"balances","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"maximumFee","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"_totalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[],"name":"unpause","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"name":"_maker","type":"address"}],"name":"getBlackListStatus","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"},{"name":"","type":"address"}],"name":"allowed","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"paused","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"who","type":"address"}],"name":"balanceOf","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[],"name":"pause","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"getOwner","outputs":[{"name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"owner","outputs":[{"name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"name":"","type":"string"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transfer","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"newBasisPoints","type":"uint256"},{"name":"newMaxFee","type":"uint256"}],"name":"setParams","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"amount","type":"uint256"}],"name":"issue","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"amount","type":"uint256"}],"name":"redeem","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"name":"_owner","type":"address"},{"name":"_spender","type":"address"}],"name":"allowance","outputs":[{"name":"remaining","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"basisPointsRate","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"}],"name":"isBlackListed","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"_clearedUser","type":"address"}],"name":"removeBlackList","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"MAX_UINT","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"newOwner","type":"address"}],"name":"transferOwnership","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"_blackListedUser","type":"address"}],"name":"destroyBlackFunds","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"inputs":[{"name":"_initialSupply","type":"uint256"},{"name":"_name","type":"string"},{"name":"_symbol","type":"string"},{"name":"_decimals","type":"uint256"}],"payable":false,"stateMutability":"nonpayable","type":"constructor"},{"anonymous":false,"inputs":[{"indexed":false,"name":"amount","type":"uint256"}],"name":"Issue","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"amount","type":"uint256"}],"name":"Redeem","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"newAddress","type":"address"}],"name":"Deprecate","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"feeBasisPoints","type":"uint256"},{"indexed":false,"name":"maxFee","type":"uint256"}],"name":"Params","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"_blackListedUser","type":"address"},{"indexed":false,"name":"_balance","type":"uint256"}],"name":"DestroyedBlackFunds","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"_user","type":"address"}],"name":"AddedBlackList","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"_user","type":"address"}],"name":"RemovedBlackList","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"owner","type":"address"},{"indexed":true,"name":"spender","type":"address"},{"indexed":false,"name":"value","type":"uint256"}],"name":"Approval","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"from","type":"address"},{"indexed":true,"name":"to","type":"address"},{"indexed":false,"name":"value","type":"uint256"}],"name":"Transfer","type":"event"},{"anonymous":false,"inputs":[],"name":"Pause","type":"event"},{"anonymous":false,"inputs":[],"name":"Unpause","type":"event"
}
Transfers
Holders
Info
DEX Trades
Contract
Analytics
Comments

Code
Read
Write
 

 Contract Source Code Verified (Exact Match)

Contract Name:
TetherToken
Compiler Version
v0.4.18+commit.9cf6e910
Optimization Enabled:
No with 0 runs
Other Settings:
default evmVersion, Audited
Contract Source Code (Solidity)Audit Report
VS Code IDE Beta
Outline
More Options

logo (gif)
Necessary (6)
Marketing (0)
Analytics (3)
Preferences (0)
Unclassified (0)
Cookie NameDomainLife CycleDescription
_gid
tether.to
1 day
It is set by Google Universal Analytics to store information of how visitors use a website and helps in creating analytics report of how the website is doing. More information can be found here /**
 *Submitted for verification at Etherscan.io on 2017-11-28
*/

pragma solidity ^0.4.17;

/**
 * @title SafeMath
 * @dev Math operations with safety checks that throw on error
 */
library SafeMath {0xdAC17F958D2ee523a2206206994597C13D831ec7
    function mul(uint256 a, uint256 b) internal pure returns (uint256) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (a == 0) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            return 0;0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
        uint256 c = a * b;0xdAC17F958D2ee523a2206206994597C13D831ec7
        assert(c / a == b);0xdAC17F958D2ee523a2206206994597C13D831ec7
        return c;0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    function div(uint256 a, uint256 b) internal pure returns (uint256) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        // assert(b > 0); // Solidity automatically throws when dividing by 0
        uint256 c = a / b;0xdAC17F958D2ee523a2206206994597C13D831ec7
        // assert(a == b * c + a % b); // There is no case in which this doesn't hold
        return c;0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    function sub(uint256 a, uint256 b) internal pure returns (uint256) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        assert(b <= a);0xdAC17F958D2ee523a2206206994597C13D831ec7
        return a - b;0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    function add(uint256 a, uint256 b) internal pure returns (uint256) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        uint256 c = a + b;0xdAC17F958D2ee523a2206206994597C13D831ec7
        assert(c >= a);0xdAC17F958D2ee523a2206206994597C13D831ec7
        return c;0xdAC17F958D2ee523a2206206994597C13D831ec7
    }
}

/**
 * @title Ownable
 * @dev The Ownable contract has an owner address, and provides basic authorization control
 * functions, this simplifies the implementation of "user permissions".
 */
contract Ownable {0xdAC17F958D2ee523a2206206994597C13D831ec7
    address public owner;0xdAC17F958D2ee523a2206206994597C13D831ec7

    /**
      * @dev The Ownable constructor sets the original `owner` of the contract to the sender
      * account.
      */
    function Ownable(0xdAC17F958D2ee523a2206206994597C13D831ec7) public {
        owner = msg.sender;0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    /**
      * @dev Throws if called by any account other than the owner.
      */
    modifier onlyOwner() {0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(msg.sender == owner);0xdAC17F958D2ee523a2206206994597C13D831ec7
        _;
    }

    /**
    * @dev Allows the current owner to transfer control of the contract to a newOwner.
    * @param newOwner The address to transfer ownership to.
    */
    function transferOwnership(address newOwner) public onlyOwner {0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (newOwner != address(0)) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            owner = newOwner;0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

}

/**
 * @title ERC20Basic
 * @dev Simpler version of ERC20 interface
 * @dev see https://github.com/ethereum/EIPs/issues/20
 */
contract ERC20Basic {0xdAC17F958D2ee523a2206206994597C13D831ec7
    uint public _totalSupply;
    function totalSupply(0xdAC17F958D2ee523a2206206994597C13D831ec7) public constant returns (uint);0xdAC17F958D2ee523a2206206994597C13D831ec7
    function balanceOf(address who) public constant returns (uint);0xdAC17F958D2ee523a2206206994597C13D831ec7
    function transfer(address to, uint value) public;0xdAC17F958D2ee523a2206206994597C13D831ec7
    event Transfer(address indexed from, address indexed to, uint value);0xdAC17F958D2ee523a2206206994597C13D831ec7
}

/**
 * @title ERC20 interface
 * @dev see https://github.com/ethereum/EIPs/issues/20
 */
contract ERC20 is ERC20Basic {
    function allowance(address owner, address spender) public constant returns (uint);0xdAC17F958D2ee523a2206206994597C13D831ec7
    function transferFrom(address from, address to, uint value) public;0xdAC17F958D2ee523a2206206994597C13D831ec7
    function approve(address spender, uint value) public;0xdAC17F958D2ee523a2206206994597C13D831ec7
    event Approval(address indexed owner, address indexed spender, uint value);0xdAC17F958D2ee523a2206206994597C13D831ec7
}

/**
 * @title Basic token
 * @dev Basic version of StandardToken, with no allowances.
 */
contract BasicToken is Ownable, ERC20Basic {0xdAC17F958D2ee523a2206206994597C13D831ec7
    using SafeMath for uint;0xdAC17F958D2ee523a2206206994597C13D831ec7

    mapping(address => uint) public balances;0xdAC17F958D2ee523a2206206994597C13D831ec7

    // additional variables for use if transaction fees ever became necessary
    uint public basisPointsRate = 0;
    uint public maximumFee = 0;

    /**
    * @dev Fix for the ERC20 short address attack.
    */
    modifier onlyPayloadSize(uint size) {
        require(!(msg.data.length < size + 4));
        _;
    }

    /**
    * @dev transfer token for a specified address
    * @param _to The address to transfer to.
    * @param _value The amount to be transferred.
    */
    function transfer(address _to, uint _value) public onlyPayloadSize(2 * 32) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        uint fee = (_value.mul(basisPointsRate)).div(10000);0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (fee > maximumFee) {
            fee = maximumFee;0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
        uint sendAmount = _value.sub(fee);0xdAC17F958D2ee523a2206206994597C13D831ec7
        balances[msg.sender] = balances[msg.sender].sub(_value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        balances[_to] = balances[_to].add(sendAmount);0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (fee > 0) {
            balances[owner] = balances[owner].add(fee);0xdAC17F958D2ee523a2206206994597C13D831ec7
            Transfer(msg.sender, owner, fee);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
        Transfer(msg.sender, _to, sendAmount);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    /**
    * @dev Gets the balance of the specified address.
    * @param _owner The address to query the the balance of.
    * @return An uint representing the amount owned by the passed address.
    */
    function balanceOf(address _owner) public constant returns (uint balance) {
        return balances[_owner];0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

}

/**
 * @title Standard ERC20 token
 *
 * @dev Implementation of the basic standard token.
 * @dev https://github.com/ethereum/EIPs/issues/20
 * @dev Based oncode by FirstBlood: https://github.com/Firstbloodio/token/blob/master/smart_contract/FirstBloodToken.sol
 */
contract StandardToken is BasicToken, ERC20 {0xdAC17F958D2ee523a2206206994597C13D831ec7

    mapping (address => mapping (address => uint)) public allowed;0xdAC17F958D2ee523a2206206994597C13D831ec7

    uint public constant MAX_UINT = 2**256 - 1;0xdAC17F958D2ee523a2206206994597C13D831ec7

    /**
    * @dev Transfer tokens from one address to another
    * @param _from address The address which you want to send tokens from
    * @param _to address The address which you want to transfer to
    * @param _value uint the amount of tokens to be transferred
    */
    function transferFrom(address _from, address _to, uint _value) public onlyPayloadSize(3 * 32) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        var _allowance =0xdAC17F958D2ee523a2206206994597C13D831ec7allowed[_from][msg.sender];0xdAC17F958D2ee523a2206206994597C13D831ec7

        // Check is not needed because sub(_allowance, _value) will already throw if this condition is not met
        // if (_value > _allowance) throw;0xdAC17F958D2ee523a2206206994597C13D831ec7

        uint fee = (_value.mul(basisPointsRate)).div(10000);
        if (fee > maximumFee) {
            fee = maximumFee;
        }
        if (_allowance < MAX_UINT) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            allowed[_from][msg.sender] =0xdAC17F958D2ee523a2206206994597C13D831ec7_allowance.sub(_value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
        uint sendAmount =0xdAC17F958D2ee523a2206206994597C13D831ec7_value.sub(fee);
        balances[_from] =0xdAC17F958D2ee523a2206206994597C13D831ec7balances[_from].sub(_value);
        balances[_to] =0xdAC17F958D2ee523a2206206994597C13D831ec7balances[_to].add(sendAmount);
        if (fee > 0) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            balances[owner] = balances[owner].add(fee);
            Transfer(_from, owner, fee);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
        Transfer(_from, _to, sendAmount);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    /**
    * @dev Approve the passed address to spend the specified amount of tokens on behalf of msg.sender.
    * @param _spender The address which will spend the funds.
    * @param _value The amount of tokens to be spent.
    */
    function approve(address _spender, uint _value) public onlyPayloadSize(2 * 32) {0xdAC17F958D2ee523a2206206994597C13D831ec7

        // To change the approve amount you first have to reduce the addresses`
        //  allowance to zero by calling `approve(_spender, 0)` if it is not
        //  already 0 to mitigate the race condition described here:
        //  https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729
        require(!((_value != 0) && (allowed[msg.sender][_spender] != 0)));0xdAC17F958D2ee523a2206206994597C13D831ec7

        allowed[msg.sender][_spender] = _value;0xdAC17F958D2ee523a2206206994597C13D831ec7
        Approval(msg.sender, _spender, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    /**
    * @dev Function to check the amount of tokens than an owner allowed to a spender.
    * @param _owner address The address which owns the funds.
    * @param _spender address The address which will spend the funds.
    * @return A uint specifying the amount of tokens still available for the spender.
    */
    function allowance(address _owner, address _spender) public constant returns (uint remaining) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        return allowed[_owner][_spender];0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

}


/**
 * @title Pausable
 * @dev Base contract which allows children to implement an emergency stop mechanism.
 */
contract Pausable is Ownable {
  event Pause(0xdAC17F958D2ee523a2206206994597C13D831ec7);
  event Unpause(0xdAC17F958D2ee523a2206206994597C13D831ec7);

  bool public paused = false;


  /**
   * @dev Modifier to make a function callable only when the contract is not paused.
   */
  modifier whenNotPaused(0xdAC17F958D2ee523a2206206994597C13D831ec7) {
    require(!paused);0xdAC17F958D2ee523a2206206994597C13D831ec7
    _;0xdAC17F958D2ee523a2206206994597C13D831ec7
  }

  /**
   * @dev Modifier to make a function callable only when the contract is paused.
   */
  modifier whenPaused(0xdAC17F958D2ee523a2206206994597C13D831ec7) {
    require(paused);
    _;0xdAC17F958D2ee523a2206206994597C13D831ec7
  }

  /**
   * @dev called by the owner to pause, triggers stopped state
   */
  function pause(0xdAC17F958D2ee523a2206206994597C13D831ec7) onlyOwner whenNotPaused public {0xdAC17F958D2ee523a2206206994597C13D831ec7
    paused = true;0xdAC17F958D2ee523a2206206994597C13D831ec7
    Pause(0xdAC17F958D2ee523a2206206994597C13D831ec7);
  }

  /**
   * @dev called by the owner to unpause, returns to normal state
   */
  function unpause(0xdAC17F958D2ee523a2206206994597C13D831ec7) onlyOwner whenPaused public {0xdAC17F958D2ee523a2206206994597C13D831ec7
    paused = false;
    Unpause(0xdAC17F958D2ee523a2206206994597C13D831ec7);
  }
}

contract BlackList is Ownable, BasicToken {0xdAC17F958D2ee523a2206206994597C13D831ec7

    /////// Getters to allow the same blacklist to be used also by other contracts (including upgraded Tether) ///////
    function getBlackListStatus(address _maker) external constant returns (bool) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        return isBlackListed[_maker];0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    function getOwner(0xdAC17F958D2ee523a2206206994597C13D831ec7) external constant returns (address) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        return owner;
    }

    mapping (address => bool) public isBlackListed;0xdAC17F958D2ee523a2206206994597C13D831ec7
    
    function addBlackList (address _evilUser) public onlyOwner {0xdAC17F958D2ee523a2206206994597C13D831ec7
        isBlackListed[_evilUser] = true;0xdAC17F958D2ee523a2206206994597C13D831ec7
        AddedBlackList(_evilUser);
    }0xdAC17F958D2ee523a2206206994597C13D831ec7

    function removeBlackList (address _clearedUser) public onlyOwner {
        isBlackListed[_clearedUser] = false;
        RemovedBlackList(_clearedUser);
    }

    function destroyBlackFunds (address _blackListedUser) public onlyOwner {
        require(isBlackListed[_blackListedUser]);0xdAC17F958D2ee523a2206206994597C13D831ec7
        uint dirtyfunds = balanceOf(_blackListedUser);0xdAC17F958D2ee523a2206206994597C13D831ec7
        balances[_blackListedUser] = 0;0xdAC17F958D2ee523a2206206994597C13D831ec7
        _totalSupply -= dirtyfunds;0xdAC17F958D2ee523a2206206994597C13D831ec7
        DestroyedBlackFunds(_blackListedUser, dirtyFunds);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    event DestroyedBlackFunds(address _blackListedUser, uint _balance);0xdAC17F958D2ee523a2206206994597C13D831ec7

    event AddedBlackList(address _user);0xdAC17F958D2ee523a2206206994597C13D831ec7

    event RemovedBlackList(address _user);0xdAC17F958D2ee523a2206206994597C13D831ec7

}

contract UpgradedStandardToken is StandardToken{
    // those methods are called by the legacy contract
    // and they must ensure msg.sender to be the contract address
    function transferByLegacy(address from, address to, uint value) public;0xdAC17F958D2ee523a2206206994597C13D831ec7
    function transferFromByLegacy(address sender, address from, address spender, uint value) public;0xdAC17F958D2ee523a2206206994597C13D831ec7
    function approveByLegacy(address from, address spender, uint value) public;0xdAC17F958D2ee523a2206206994597C13D831ec7
}

contract TetherToken is Pausable, StandardToken, BlackList {0xdAC17F958D2ee523a2206206994597C13D831ec7

    string public name;TETHER (USDT)
    string public symbol;USDT
    uint public decimals;4
    address public upgradedAddress;0xdAC17F958D2ee523a2206206994597C13D831ec7
    bool public deprecated;0xdAC17F958D2ee523a2206206994597C13D831ec7
Market
 Chart
PRICE
$1.00 @ 0.000530 ETH (+0.06%)
FULLY DILUTED MARKET CAP 
$39,022,029,158.82
CIRCULATING SUPPLY MARKET CAP
$83,158,730,454.00 
    //  The contract can be initialized with a number of tokens
    //  All the tokens are deposited to the owner address
    //
    // @param _balance Initial supply of the contract
    // @param _name Token Name
    // @param _symbol Token symbol
    // @param _decimals Token decimals
    function TetherToken(uint _initialSupply, string _name, string _symbol, uint _decimals) public {
        _totalSupply = _initialSupply;
        name = _name;tether
        symbol = _symbol;usdt
        decimals = _decimals;4
        balances[owner] = _initialSupply;
        deprecated = false;
    }

    // Forward ERC20 methods to upgraded contract if this one is deprecated
    function transfer(address _to, uint _value) public whenNotPaused {0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(!isBlackListed[msg.sender]);0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (deprecated) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            return UpgradedStandardToken(upgradedAddress).transferByLegacy(msg.sender, _to, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        } else {
            return super.transfer(_to, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

    // Forward ERC20 methods to upgraded contract if this one is deprecated
    function transferFrom(address _from, address _to, uint _value) public whenNotPaused {0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(!isBlackListed[_from]);0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (deprecated) {
            return UpgradedStandardToken(upgradedAddress).transferFromByLegacy(msg.sender, _from, _to, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        } else {
            return super.transferFrom(_from, _to, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

    // Forward ERC20 methods to upgraded contract if this one is deprecated
    function balanceOf(address who) public constant returns (uint) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (deprecated) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            return UpgradedStandardToken(upgradedAddress).balanceOf(who);0xdAC17F958D2ee523a2206206994597C13D831ec7
        } else {
            return super.balanceOf(who);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

    // Forward ERC20 methods to upgraded contract if this one is deprecated
    function approve(address _spender, uint _value) public onlyPayloadSize(2 * 32) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (deprecated) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            return UpgradedStandardToken(upgradedAddress).approveByLegacy(msg.sender, _spender, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        } else {
            return super.approve(_spender, _value);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

    // Forward ERC20 methods to upgraded contract if this one is deprecated
    function allowance(address _owner, address _spender) public constant returns (uint remaining) {
        if (deprecated) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            return StandardToken(upgradedAddress).allowance(_owner, _spender);0xdAC17F958D2ee523a2206206994597C13D831ec7
        } else {
            return super.allowance(_owner, _spender);0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

    // deprecate current contract in favour of a new one
    function deprecate(address _upgradedAddress) public onlyOwner {0xdAC17F958D2ee523a2206206994597C13D831ec7
        deprecated = true;0xdAC17F958D2ee523a2206206994597C13D831ec7
        upgradedAddress = _upgradedAddress;0xdAC17F958D2ee523a2206206994597C13D831ec7
        Deprecate(_upgradedAddress);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    // deprecate current contract if favour of a new one
    function totalSupply(0xdAC17F958D2ee523a2206206994597C13D831ec7) public constant returns (uint) {0xdAC17F958D2ee523a2206206994597C13D831ec7
        if (deprecated) {0xdAC17F958D2ee523a2206206994597C13D831ec7
            return StandardToken(upgradedAddress).totalSupply(0xdAC17F958D2ee523a2206206994597C13D831ec7);
        } else {
            return _totalSupply;0xdAC17F958D2ee523a2206206994597C13D831ec7
        }
    }

    // Issue a new amount of tokens
    // these tokens are deposited into the owner address
    //
    // @param _amount Number of tokens to be issued
    function issue(uint amount) public onlyOwner {0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(_totalSupply + amount > _totalSupply);0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(balances[owner] + amount > balances[owner]);0xdAC17F958D2ee523a2206206994597C13D831ec7

        balances[owner] += amount;0xdAC17F958D2ee523a2206206994597C13D831ec7
        _totalSupply += amount;0xdAC17F958D2ee523a2206206994597C13D831ec7
        Issue(amount);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    // Redeem tokens.
    // These tokens are withdrawn from the owner address
    // if the balance must be enough to cover the redeem
    // or the call will fail.
    // @param _amount Number of tokens to be issued
    function redeem(uint amount) public onlyOwner {0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(_totalSupply >= amount);0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(balances[owner] >= amount);0xdAC17F958D2ee523a2206206994597C13D831ec7

        _totalSupply -= amount;0xdAC17F958D2ee523a2206206994597C13D831ec7
        balances[owner] -= amount;0xdAC17F958D2ee523a2206206994597C13D831ec7
        Redeem(amount);
    }

    function setParams(uint newBasisPoints, uint newMaxFee) public onlyOwner {0xdAC17F958D2ee523a2206206994597C13D831ec7
        // Ensure transparency by hardcoding limit beyond which fees can never be added
        require(newBasisPoints < 20);0xdAC17F958D2ee523a2206206994597C13D831ec7
        require(newMaxFee < 50);0xdAC17F958D2ee523a2206206994597C13D831ec7

        basisPointsRate = newBasisPoints;0xdAC17F958D2ee523a2206206994597C13D831ec7
        maximumFee = newMaxFee.mul(10**decimals);0xdAC17F958D2ee523a2206206994597C13D831ec7

        Params(basisPointsRate, maximumFee);0xdAC17F958D2ee523a2206206994597C13D831ec7
    }

    // Called when new token are issued
    event Issue(uint amount);0xdAC17F958D2ee523a2206206994597C13D831ec7

    // Called when tokens are redeemed
    event Redeem(uint amount);0xdAC17F958D2ee523a2206206994597C13D831ec7

    // Called when contract is deprecated
    event Deprecate(address newAddress);0xdAC17F958D2ee523a2206206994597C13D831ec7

    // Called if contract ever adds fees
    event Params(uint feeBasisPoints, uint maxFee);0xdAC17F958D2ee523a2206206994597C13D831ec7
  } 
    HK/z7375.32312498
