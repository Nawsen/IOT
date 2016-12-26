## IOT

## Install / Development

```bash

# Install dependencies
npm install

# start server
npm run start

# Client url: http://localhost:4200
# Application ( express ) API: http://localhost:4300
```

## Build / Production

```bash

npm run build

## Deploy dist folder to app server

Structure of dist folder:

/dist/server <-- expressjs
/dist/client <-- angular2

## Production

NODE_ENV=production node ./dist/server/bin/www

```
