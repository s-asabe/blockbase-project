Name: prajwal
Wallet Address:0x1dcC55646d8A2820c7051a24B6B129Ea4681f4B5
✅ Features Implemented
Solidity Feature:
Get your own name – Added a function getMyName() in the smart contract to fetch the name associated with the wallet.
JavaScript Feature:
Display connected wallet address – Shows the wallet address of the currently connected MetaMask user.
🛠 Code Changes
Solidity Code:
function getMyName() public view returns (string memory) {
    return people[msg.sender].name;
}
