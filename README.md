# Expense Tracker DApp


1. **Get Total Registered Users**  
   - Added view function to fetch total registered users count
   - Returns `uint256` count from `registeredPeople` array

```solidity
 In ExpenseTracker.sol
function getTotalRegisteredUsers() public view returns (uint256) {
    return registeredPeople.length;
}
2.
// In App.js,added a copy button too
{isConnected && (
  <div className="wallet-display">
    <span>Connected: {account}</span>
    <button onClick={() => navigator.clipboard.writeText(account)}>
      📋 Copy
    </button>
  </div>
)}
