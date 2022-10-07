###### Tonfera ##########

WELCOME TO TONFERA CODE REP

To run the frontend cd into the client folder and do the following

-Install nodemodules through running  yarn

-start the server through   yarn dev

-The web application will run on port 3000

-Go to your browser and open that port 3000

To run the smart contract you should do the following

-you should install ganache

-have metamask installed in your browser

-install truffle globally 

-Go to the root of the project 

-run truffle compile

-run truffle migrate --reset


env.local // these env variables should be put in the root of the client project
WEB3_STORAGE_API_TOKEN  = this is got from web3 storage website

NEXT_PUBLIC_APP_URL = http://localhost:3000

NEXT_PUBLIC_BLOCKCHAIN_URL = http://127.0.0.1:7545

NEXT_PUBLIC_REPORT_LIMIT   =   100


env // these variables should be put on the root of the entire project
MNEMONIC =  734fd541ef5ee0ead4dcbc1a97d6611164b62eff62f60ea63c90cb34f389269e
