notes - Nov 2023

```bash
$ nvm use v18
N/A: version "v18" is not yet installed.

```

Error: error:0308010C:digital envelope routines::unsupported
    at new Hash (node:internal/crypto/hash:69:19)

add to package.json start script:
```bash
--openssl-legacy-provider
```

```bash
$ npm run server
ERROR: npm v10.2.4 is known not to run on Node.js v14.21.3.  This version of npm supports the following node versions: `^18.17.0 || >=20.5.0`. You can find the latest version at https://nodejs.org/.
```

had to run 
```bash
nvm use v18 
```
in other terminal :)



---


# React Crash Course 2021 (Task Tracker App)

This is the project from the [YouTube crash course](https://www.youtube.com/watch?v=w7ejDZ8SWv8). It includes the react ui as well as JSON-server for our mock backend

## Usage

### Install dependencies

```
npm install
```

### Run React dev server (http://localhost:3000)

```
npm start
```

### Run the JSON server (http://localhost:5000)

```
npm run server
```

### To build for production

```
npm run build
```
