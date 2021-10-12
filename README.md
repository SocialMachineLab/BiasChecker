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

## How to cite this work?

There are two main references for this work: Paper [1] carries out a study on personalisation on Twitter using a previous version of the BiasChecker tool whereas paper [2] introduces the BiasChecker tool and its architecture.


```
[1] Jonatas C. dos Santos, Sean W. M. Siqueira, Bernardo Pereira Nunes, Pedro P. Balestrassi, Fabrício R. S. Pereira:
Is There Personalization in Twitter Search? A Study on polarized opinions about the Brazilian Welfare Reform. WebSci 2020: 267-276

[2] TODO / ASONAM

```

```
@inproceedings{DBLP:conf/websci/SantosSNBP20,
  author    = {Jonatas C. dos Santos and
               Sean W. M. Siqueira and
               Bernardo Pereira Nunes and
               Pedro P. Balestrassi and
               Fabr{\'{\i}}cio R. S. Pereira},
  editor    = {Emilio Ferrara and
               Pauline Leonard and
               Wendy Hall},
  title     = {Is There Personalization in Twitter Search? {A} Study on polarized
               opinions about the Brazilian Welfare Reform},
  booktitle = {WebSci '20: 12th {ACM} Conference on Web Science, Southampton, UK,
               July 6-10, 2020},
  pages     = {267--276},
  publisher = {{ACM}},
  year      = {2020},
  url       = {https://doi.org/10.1145/3394231.3397917},
  doi       = {10.1145/3394231.3397917},
  timestamp = {Thu, 07 Oct 2021 07:49:23 +0200},
  biburl    = {https://dblp.org/rec/conf/websci/SantosSNBP20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
