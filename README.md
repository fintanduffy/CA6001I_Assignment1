# CA6001I_Assignment1

Enure you have the metamask extension installed on your browser.

Install node js : 
>$ sudo apt install nodejs

Install node package manager:
>$ sudo apt install npm

Install Ganache CLI
>$ npm install -g ganache-cli

Install the Ganache UI: https://www.trufflesuite.com/ganache

Create a local project directory
>$ mkdir CA6001I_Assignment1

Change directory to the local project directory
>$ cd CA6001I_Assignment1

Clone the git repository:
>$ git clone https://github.com/fintanduffy/CA6001I_Assignment

Note that this project has a number of dependencies that have already been included in the node_modules within the git repo:
- OpenZepplin
- Truffle Wallet Provider
- DotEnv
- Lite dev server

To compile the project run:
>$ truffle compile

To run the test scripts, run:
>$ truffle test

To migrate to your local development network using Ganage, ensure that you have launched the Ganache UI.
Then run:
>$ truffle migrate

After the successful migration you may launch the application using lite server:
>$ npm run dev

This will invoke the web app.

Add the local instance of Ganache to your Metamask wallet.

Next you need to import the Ganache account[0] and account[1] into your metamask wallet.
Ensure both accounts are connected.
Select the account linked to Ganache account[0].

Return to the web app and refresh the page.
You should note that the account balance of 1,000,000 tokens is displayed.
The application is now ready for use.

A demonstration of how to use the application is available at:
https://www.loom.com/share/8589ff3ce46648269a61135bba398a46

