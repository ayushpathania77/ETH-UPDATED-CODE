# ETH-Assesment

Metacrafters Ethereum Assessment to create our own token.

## Description

In this assessment we have created a contract named 'MY MytokenRuppes'. The contract consists of token details such as token name,token abbreviation and total-for keeping count of tokens present in the network. A 'balance' variable is used for mapping any address to integer value. 
The contract consists of 2 functions - mint and burn. The 'mint' function is used to generate tokens. This function takes two parameters-address and value. This function increaments the total count by the value passed in 'value' variable. Additionaly this mint function increments the balance of the address passed by the value passed.
The burn function is exactly opposite to the mint function. It is used to burn/destroy tokens. This function also takes the same parameters used in the mint function but it decrements the total count and balance by the value passed only if the balance of the address is greater than or equal to the value.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., metacrafetToken.sol). Copy and paste the code given in the "ABCXXX.sol" file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.26" (or another compatible version), and then click on the "Compile metacrafetToken.sol " button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "metacrafetToken.sol" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint function,burn function by mentioning address and value.For e.g: click on the downward arrow at right of mint. You will see space for providing address and value. Pass any address and value and click transact button. You will see that the function is executed and tokens are minted. To verify this paste the same address in the balance bar and click on it. You will see the balance returns value equal to the value passed in mint function. You can also see the token name, abbreviation and total count by clicking on them.

## Authors

Ayush Pathania
[@ayushpathania77]


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
