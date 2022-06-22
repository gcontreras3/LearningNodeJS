# LearningNodeJS
When you install Node.js you get what is called an NPM - Also known as "Node Package Manager".
When Packages are installed they get stored into a folder called "node_modules" folder.
Any package or dependencies are listed in a "package.json" file
NPM scripts can be created to run certain tasks such as run a server

npm init    Generates a package.json file
npm install express     installs a package locally
npm install -g nodemon      installs a package globally

- Node Modules -
Node Core Modules ( path, fs, http, etc )

3rd party modules/packages installed via NPM
Custom modules (files)

const path = require('path');
const myFile = require('./myFile');

Let's Jump in...

Install Node.JS     11.9.0
Open up command line        Node comes with a repl (Read, Eval, Print, Loop) allows us to run JavaScript inside the console.
Check node --version
check npm --version
To access the repl >>> node

> 1 + 1
2
> const name = 'Jerry'
undefined
> console.log(name)
Jerry
Undefined
> function hello(){ return 'Hello ' + name }
undefined
> hello()
Hello Jerry

Create a package.json file
npm init
