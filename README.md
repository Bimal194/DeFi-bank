
This project is inspired by compound protocol (https://compound.finance/) which is called a money market protocol.
Essentially, our DeFi-bank is decentralised application which will used to calculate the interest on a given token balance.
Here, the calculation of interests is based on compound Interest.
For this particular app, we are calculating final amount by considering 1% interest every second.

Note:
*A decentralized application (dApp) is a type of distributed open source software application that runs on a peer-to-peer (P2P) blockchain network rather than on a single computer. DApps are visibly similar to other software applications that are supported on a website or mobile device but are P2P supported.*

# Techstacks:
HTML, CSS, Javascript, Motoko programming language


Motoko Programming language is a new, modern and type safe language for developers who want to build the next 
generation of distributed applications to run on the Internet Computer (ICP) blockchain Network.

# Deployment to the ICP Live Blockchain
For deployment purpose, we need ICP Tokens
so there are various methods to get this tokens
like, 
* Purchase/exchange coins with ICP tokens.
* Get tokens from NNS(Network Nervous System) through Voting.
* Dfinity Developer Grant Program.
* And those who have their own data-centers.

All the above methods are not free of cost.
So, there is one free way to get $20 worth of free cycles.
*Cycles Faucet: https://internetcomputer.org/docs/current/developer-docs/quickstart/cycles-faucet/ .*
Again there is some conditions are there like you should have more than 90 days old twitter account.
And twitter account has to be active over last 30 days.


![gif_final](https://user-images.githubusercontent.com/69100830/177812262-e9f44398-d8a8-45ed-b6ab-bd5bdb37fca7.gif)

For running app locally ,we have two methods :
* From command line, we will use below two commands in different wsl cmd lines.
 ``` dfx start```
 ``` dfx deploy```


* For better User Interface we can use Candid UI.
  for running Candid UI, we have to follow some steps given below.
      * ```dfx canister id __Candid_UI```     [for getting canister Id].

      * -Paste url on browser: ```http://127.0.0.1.8000/?canisterId=<YOUR CANISTER ID>```.

      * ```dfx canister id <YOUR APP NAME>``` [for getting id to provide in Candid UI box].

![candid UI](https://user-images.githubusercontent.com/69100830/177814899-726ed3b8-0b44-4093-86e1-9dc5b83f11e1.jpg)

------------------------------------------------------------------------------------------------------------------------------



 
