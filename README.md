# Whitelist-dApp

> First, you need to create a Whitelist-Daap folder where the Hardhat project and your Next.js app will later go.

> Then, in Whitelist-Daap folder, you will set up Hardhat project.

> In the same directory where you installed Hardhat run command `npx hardhat`, Create a basic sample project. 

> Start by creating a new file inside the `contracts` directory called `Whitelist.sol`.

>  To deploy the contract at rinkeby network, Create a new file named `deploy.js` under the `scripts` folder.

>  Now create a `.env` file in the `hardhat-tutorial` folder, add your (NETWORK URL) AND (PRIVATE KEY) in the env file.

> Now we will install `dotenv` package to be able to import the env file and use it in our config. Open up a terminal pointing at `hardhat-tutorial` directory and execute this command `npm install dotenv`

> Compile the contract, open up a terminal pointing at `hardhat-tutorial` directory and execute the `npx hardhat compile` command.

> To deploy, open up a terminal pointing at `hardhat-tutorial` directory and execute this `npx hardhat run scripts/deploy.js --network rinkeby` command.
