Looking at https://auth0.com/blog/node-js-and-typescript-tutorial-build-a-crud-api/

- init with npm
- `npm init -y`
  - automatically answer yes to all prompts
- `npm i express dotenv cors helmet`
  - essentials
- install typescript locally
  - `npm i -D typescript `
- get typed versions of other packages
  - `npm i -D @types/node @types/express @types/dotenv @types/cors @types/helmet`
- initialize tsconfig file
  - `npx tsc --init`
- add ts-node-dev for watch mode
  - `npm i -D ts-node-dev`


COMMANDS
- `npm run dev`
  - restars with file changes because of package.json script