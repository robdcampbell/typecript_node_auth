# Notes for TS_API Project


# Generate new keys (Access Tokens): https://travistidwell.com/jsencrypt/demo/

# Base64 encode the keys: https://www.base64encode.org/


## Steps

## Init TypeScript
- 1)  Create tsconfig.json file
    - npx typescript --init (didn't work!)
    - Got error (tested npx with : npx cowsay wow)
    - Solution, use this instead: npx tsc --init

### Install dev dependencies
- 2)  npm install typescript ts-node-dev @types/express @types/config pino-pretty @types/nodemailer @types/lodash @types/jsonwebtoken -D

## Install Express
- 3) npm install express@5.0.0-alpha.8

### Install dependencies
- 4)  npm install mongoose @typegoose/typegoose config argon2 pino dayjs nanoid nodemailer lodash jsonwebtoken dotenv zod