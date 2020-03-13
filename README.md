# 2PG
Simple multi-purpose Discord bot made with TypeScript

## Installation
1) Fork/download this respository
2) `npm i` to install packages

## Hosting
- Remember to have a local MongoDB database running `mongod`
1) `npm start` to start the bot

## Troubleshooting
- Open an issue, if you find any bugs or have any suggestions etc.

### Common Errors
`UnhandledPromiseRejectionWarning: MongooseServerSelectionError: connect ECONNREFUSED 127.0.0.1:27017`

**Possible Cause**: No MongoDB server instance running, start with `mongod`