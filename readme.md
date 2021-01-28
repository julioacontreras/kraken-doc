# KrakenJs

## Get Started

### Install

To get started your project:
``` bash
git clone https://github.com/julioacontreras/kraken
cd kraken
npm i
```

### Hellow world

Create `.env` file:
``` bash
PROTOCOL=http
HOST=localhost
PORT=3000
APP_URL=http://localhost
```

Create my module:
``` bash
npm run create-module myModule
-------------------------
✔ Created module.
- src
 - modules
  - myModule 
    - controllers
    - domains
    - models
    - register
    - routes
    - services
    - tests
✔ Updated configuration.
* Ready to use.
-------------------------
```

Run the application:
``` bash
npm run dev
```

## Commands

``` bash
#Run application in developmente mode
$ npm run dev

#Run dev mode restarting whe change some file
$ npm run watch

# Deploy
$ npm run start

# Run tests
$ npm run test
```
