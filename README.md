# eth-avax_module1

ErrorHandling Contract This is a Solidity smart contract that demonstrates use of assert, revert, and require statements.

License This contract is using the MIT License.

Prerequisites Solidity ^0.8.26

Contract Details The ErrorHandlingContract is a smart contract that manages a balance variable. The deposit function allows users to add funds to the balance, but it requires the deposit amount to be greater than zero. The withdraw function lets users withdraw funds from the balance, but it checks if the withdrawal amount is greater than the available balance. If it is, the transaction is reverted with an "Insufficient balance" error message. The checkBalance function returns the current value of the balance variable, but it also uses an assert statement to ensure the balance is always greater than or equal to zero. Overall, the contract implements basic error handling and validation using the require(), assert(), and revert() statements to ensure proper behavior and prevent incorrect operations.

Video Walkthrough

https://www.loom.com/share/101e30129d624e49b5d9d04a6b170bb8?sid=fcfd9d92-0eff-4bff-a75a-b70b6b5e90bc
