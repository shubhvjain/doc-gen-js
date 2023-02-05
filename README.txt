Document generation progam in node

.[Intallation]
- Get a copy of the code : `git clone https://github.com/shubhvjain/doc-gen-js.git`
- Run  : `npm install`

.[the CLI]
- the app is accessed via command line interface. To use the `gen-doc` command throughout, the path of cli.js must be included in the env path of the OS
- `doc-gen info` : displays how to use the cli 

=====

Dev Related : 

.[File structure]
- doc-types : this folder contains various doc generation scripts. there is also an index file where all active doc gen scripts must be registered
- block : this contains the block program 
- templates : contains all the templates used by the scripts in the doc-gen folder
- utils : contains common utility functions that can be used in doc gen scripts