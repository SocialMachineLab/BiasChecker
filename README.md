# BiasChecker
BiasChecker follows a distributed and extendable architecture that allows us to simulate users following and unfollowing accounts, search for different polarised topics in a concurrent manner and measure bias. It may be applied to multiple social media platforms.



## Installation

```console
git clone https://github.com/yangcandoit/BiasChecker.git
```

open the BiasChecker folder

open one terminal
```console
cd manager

npm install --dependencies ## install dependencies of this project

npm start ## start the manager
```
open another terminal
```console
cd manager 
node server.js   ## start the server
```
open another terminal(the number of terminals is dependent on the experiment)
```console
cd agent
npm install --dependencies ## install dependencies of this project

node index.js ## start agent
```
