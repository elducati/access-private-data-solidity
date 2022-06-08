# Basic Sample Accessing 'private' data Project

This project demonstrates Accessing 'private' data.

This is a simple contract, along with a Hardhat Test, to demonstrate this. The contract will attempt to store data in private variables hoping that nobody will be able to read it's value.

The contract will take in 'password' and 'username' in its contructor and will store them in private variables.

User will somehow be able to access those 'private' variables.

Run 'npx hardhat test'

If the tests pass, it means we were successfully able to read the values of the private variables directly without needing to call functions on the contract at all.


## Prevention

NEVER store private information on a public blockchain. No other way around it.
