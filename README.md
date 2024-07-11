# Clone of DeFI Kingdom
In this project of module 1 of AVAX PROOF: Advanced Avalanche Course by Metacrafters we are going to clone the DeFI Kingdom on Avalanche.  In this digital realm, players can collect, build, and battle with their digital assets, earning rewards through various game activities.The possibilities are endless. You can create different game activities such as battling, exploring, and trading, all with rewards distributed in the form of tokens 🪙. Players can use these tokens to purchase in-game assets or trade with others.

# Description
DeFi Kingdoms is a highly complex decentralized finance application that cannot be fully comprehended in just a few hours. Therefore, in this discussion, we will only be covering the fundamentals related to custom subnet development, as this is what we are most interested in learning about. [If you're looking to gain a more comprehensive understanding of the platform, we highly recommend reading the official documentation](https://docs.defikingdoms.com/). There is a wealth of information available that can help you gain insight into how it was implemented and how you can build on top of it if you're interested. So let's focus on the custom subnet development aspects of DeFi Kingdoms and explore the exciting opportunities and possibilities that this feature offers.

By utilizing the EVM Subnet, you can deploy your smart contracts to a custom chain with low fees and your own custom token. With this power, you can architect and customize your game as you see fit.The possibilities are endless. You can create different game activities such as battling, exploring, and trading, all with rewards distributed in the form of tokens 🪙. Players can use these tokens to purchase in-game assets or trade with others. To create an immersive user experience, you can implement features such as leaderboards, achievements, and varying levels of difficulty. You can even integrate with the Avalanche wallet, allowing players to effortlessly store and manage their assets.

# Getting Started
Here's a overview of the steps you need to take:
1. <ins>**Set up your EVM subnet**</ins>: You can use our guide and the Avalanche documentation to create a custom EVM subnet on the Avalanche network.
2. <ins>**Define your native currency**</ins>: You can set up your own native currency, which can be used as the in-game currency for your DeFi Kingdom clone.
3. <ins>**Connect to Metamask**</ins>: Connect you EVM Subnet to metamask, this can be done by following the steps laid out in our guide.
4. <ins>**Deploy basic building blocks**</ins>: You can use Solidity and Remix to deploy the basic building blocks of your game, such as smart contracts for battling, exploring, and trading. These contracts will define the game rules, such as liquidity pools, tokens, and more.

## Creating EVM Subnet
1. <ins>**Install the Avalanche CLI tool**</ins>: To get started, you will need to install the Avalanche Command Line Interface (CLI) tool. This tool is used to interact with the Avalanche network from your terminal. [You can find installation instructions for the Avalanche CLI in the official documentation](https://docs.avax.network/tooling/cli-guides/install-avalanche-cli).
2. <ins>**Create a new subnet**</ins>: Once you have the Avalanche CLI installed, you can create a new subnet by running the command avalanche subnet create mySubnet in your terminal. This will create a new subnet with the name "mySubnet" on your local machine.
3. <ins>**Select the EVM Subnet option and configure**</ins>: When creating a new subnet, you will be prompted to select a subnet type. Choose the SubnetEVM option to create an EVM Subnet on your local machine and follow the steps in the image below:
```
1 avalanche subnet create mySubnet
2 Attempted to check if a new version is available, but couldn't find the currently running version information
3 Make sure to follow official instructions, or automatic updates won't be available for you
4 ✔ Subnet-EVM
5 creating subnet mySubnet
6 Enter your subnet's ChainId. It can be any positive integer.
7 ChainId: 12345567
8 Select a symbol for your subnet's native token
9 Token symbol: MYSUBNET
10 ✔ Use latest version
11 ✔ Low disk use    / Low Throughput    1.5 mil gas/s (C-Chain's setting)
12 ✔ Airdrop 1 million tokens to the default address (do not use in production)
13 ✔ No
```
4. <ins>***Deploy the subnet**</ins>: After selecting the EVM Subnet option, you can deploy the subnet by running the command avalanche subnet deploy mySubnet and selecting to deploy your subnet on your local network. This will deploy your new EVM Subnet on your local machine.
5. <ins>**View subnet details**</ins>: Once your EVM Subnet is deployed, the console will display all the details about the subnet you just created. You can use this information to interact with the subnet and start building your smart-contract protocol.

By following these simple steps, you can quickly and easily create your own EVM Subnet on the Avalanche network

## Connect to Metamask
After deploying your subnet, you will be able to see the browser extension connection details at the bottom of the console. These details can be used to connect your subnet to a wallet such as Metamask. It also includes a private key to access funds and interact with your blockchain.

Here are the connection details that you need to connect your subnet to Metamask:

<ins>**NOTE: Don't copy these values. Use the ones that your subnet provides To connect your subnet to Metamask, follow these steps:**</ins>
```
Browser Extension connection details (any node URL from above works):
RPC URL:          http://127.0.0.1:9650/ext/bc/SPqou41AALqxDquEycNYuTJmRvZYbfoV9DYApDJVXKXuwVFPz/rpc
Funded address:   0x8db97C7cEcE249c2b98bDC0226Cc4C2A57BF52FC with 1000000 (10^18) - private key: 56289e99c94b6912bfc12adc093c9b51124f0dc54ac7a766b2bc5ccf558d8027
Network name:     mySubnet
Chain ID:         54325
Currency Symbol:  TUTORIAL
```
By following these steps, you will be able to connect your subnet to Metamask and start interacting with your blockchain.

1. Open Metamask on your web browser.
2. Go to Networks > Add a network > Add a network manually.
3. Enter the details provided by the Avalanche CLI.
4. Click on "Save" to add the subnet to Metamask.

# Tools Used
* Unix Computer (MacOS or Linux)  **<ins>Here I used Ubuntu 22.04.3 LTS. You can download it from Microsoft Store</ins>**
* Solidity
* Remix
* Metamask
* Web Browser

# Steps
1. Deploy your EVM subnet using the Avalanche CLI
2. Add your Subnet to Metamask: 
    Make sure it is your selected network in Metamask
3. Connect Remix to your Metamask: 
    Use the Injected Provider
4. Deploy the smart-contracts
5. Test you application: 
    Using remix to interact with your deployed smart-contracts, deploy tokens, pools, and more.

# HELP
1. Add the network details to Metamask which details have been shown in Ubuntu Terminal.
2. Import the account in which you have 1000000 token using the private key.
3. Remember to use Injected-Provider Metamask in Environment in Remix.

# Author
Rahul Berwal <br />
[tobiasrahul](https://github.com/tobiasrahul)

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
