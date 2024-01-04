# ethers-simple-storage

# Requirement 
```.git```
you can run git --version and you see a response like git version x.x.x<br>
```Nodejs```
node --version and get an ouput like: vx.x.x<br>
```Yarn ```
yarn --version and get an output like: x.x.x<br>
```Ganache```
For RPC Server & Account



clone the Reposotoriy using <br>
``` git clone https://github.com/zafiqul/ethers-simple-storage ``` <br>
change the directory by using<br>
``` cd ethers-simple-storage ```<br>
use ``` yarn ``` to install dependency <br>
use ``` node deploy.js``` to run the project  

## Note
you need JsonRpcUrl & Private_Key to run the project you can simply install Ganche then quickstart etherium copy the RPC Server go to deploy.js file paste in JsonRpcProvider() methode then from ganche grab a account private key paste it in the wallet save and you are good to go 
``` js 
async function main() {
  let provider = new ethers.JsonRpcProvider(); // paste here RPC Server address
  let wallet = new ethers.Wallet(); //paste here Private Key from account
```
