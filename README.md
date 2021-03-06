# cryptocurrency
cryptocurrency OOP based on blockchain, using vanilla JavaScript

-   keys generated using [`elliptic`](https://github.com/indutny/elliptic)

-   testing framework: [`jest`](https://www.npmjs.com/package/jest)

-   import API collection from [`Postman collection`](https://www.getpostman.com/collections/762639b43411e76d2e67)

### Features

-   Records and assists `Transactions`

-   Maintains client `Wallet`

-   Sync `TransactionPool` instances and `Blockchain` instances across all peers

README of this repo ends here unless you're more curious to stalk or you're lost

---

## Based on : [`blockchain`](https://github.com/daby310/cryptocurrency)

to install dep.

> npm install

to run tests

> npm run test

to start api server

> npm run dev

to start peer api server

> npm run dev-peer

### Requirements

For development, you will only need Node.js.

<details>
    <summary>
    Node
    </summary>
    <br>
    
-   #### Node installation on Windows

    Just go on [official Node.js website](https://nodejs.org/) and download the installer.
    Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

-   #### Node installation on Ubuntu

    You can install nodejs and npm easily with apt install, just run the following commands.

        $ sudo apt install nodejs
        $ sudo apt install npm

-   #### Other Operating Systems
    You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

---

### Install

    $ git clone https://github.com/daby310/blockchain.git
    $ cd blockchain
    $ npm install

### Configure app

-   blockchain logic config [`./blockchain_logic/config.js`](https://github.com/daby310/blockchain/blob/master/blockchain_logic/config.js)

-   api constants config [`./api/api_config.js`](https://github.com/daby310/blockchain/blob/master/api/api_config.js)

</details>
