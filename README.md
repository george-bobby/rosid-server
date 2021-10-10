# Demo of rosid using SCSS handler
## Get started
Clone and run 
```
npm install
```  
and to start Rosid 
``` 
./node_modules/.bin/rosid serve src/ --open
```
And to compile
```
./node_modules/.bin/rosid compile src/ dist/
```
## How does it work?

Rosid starts a server and compares requested URLs with [user-defined patterns](docs/Routes.md). An associated [file handler](docs/Handlers.md) will be executed when a pattern matches. The handler receives information about the request and can transform the file, which will be sent to the browser.
## Requirements

Rosid depends on...

- [Node.js](https://nodejs.org/en/) (v8.9.0 or newer)
- [npm](https://www.npmjs.com)

## You're done.
# Credits
https://github.com/electerious/Rosid
