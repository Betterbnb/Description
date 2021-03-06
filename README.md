# Project Name

> Betterbnb

## Related Projects

  - https://github.com/Betterbnb/description.git
  - https://github.com/Betterbnb/gallery.git
  - https://github.com/Betterbnb/reviews.git
  - https://github.com/Betterbnb/booking.git

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> Some usage instructions

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- etc

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
npm install -g node-mongo-seeds
npm install -g gulp

npm run start-db
npm run start
```

For Developement:

```sh
Generate mock data:
node ./description_data_generator.js

Seed data:
npm run seed

To start database & db-client:
mongod
mongo --host 127.0.0.1:27017

To start server:
npm run start

To transpile client files:
npm run react-dev

Test:
npm run test

```

## Link to Deployed Service

http://betterbnbdescriptionserver-env.up4m7x289b.us-west-1.elasticbeanstalk.com/100/

