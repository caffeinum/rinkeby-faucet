# rinkeby token faucet

It distributes your custom tokens when you touch endpoint:

    /faucet?address=0xYOURADDRESS

To run:

    # 1. Clone the repo

    git clone git@github.com:caffeinum/rinkeby-faucet.git

    # 2. Create .env file with the following variables:

    vim .env

Environment variables:

    TOKEN_CONTRACT_OWNER_PRIVATE_KEY=
    TOKEN_CONTRACT_OWNER_ADDRESS=
    TOKEN_CONTRACT_ADDRESS=

Then:

    # 3. Install required packages and run server

    npm install
    npm start

    # >>> Server started! At http://localhost:3002
