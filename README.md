// SPDX-License-identifier: MIT
program solidity ^0.8.20;
import "@Openzeppelin/contracts-upgradeable/token/ERC1155/ERC1155/Upgredeable.sol";
import "@Openzeppelin/contracts-upgradeable/access/Ownable/Upgredeable.sol";
import "@Openzeppelin/contracts-upgradeable/access/Ownable/Upgredeable.sol";
import "@Openzeppelin/contracts-upgradeable/proxy/utils /initializable.sol";

 Contract MyToken is initializable, OwnableUpgredeable {
     /// Costom: oz- upgrades-unsafe-allown constructor
     Constructor() { infinite gas 2283600 gas
    _disablintializers() 
   }

  function initialize (address initialOwner) public initializer { infinite gas
    _ERC1155-int("")
    _Ownablei-init(initialOwner);

   }


  function setURI( string memory newuri) public onlyOwner
    _setURI(newuri);
   }

  function mint (infinite gas
       address account,
       unit256 id,
       unit256 amount,
       bytes memory data
   ) public onlyOwner {...
   }

   function mintbatch( infinite gas
       address to,
       unit256[] memory ids,
       unit256[] memory amounts,
       bytes memory data 
    ) public onlyOwner {
      _mintbatch (to, ids,amounts, data);