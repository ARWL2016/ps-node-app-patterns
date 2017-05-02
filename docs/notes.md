#### Eslint 
- Eslint and its various packages can be installed globally, as can eslint-watch. 
- running eslint --init will then create a local config file 
- to run eslint-watch, use the command esw file.js --watch - it will also run eslint normally without the watch flag 
- eslint-watch seems to require a local install of eslint 

#### Modules 
- instead of requiring an individual file, you can also require a folder which contains an index.js file. This is included by default. 
- index.js is an entry point to a module  
- a module can contain its own package.json (in the root). The main key will then indicate the entry point of this module and be served automatically. 
- the index.js file is the entry point or PUBLIC API of the module