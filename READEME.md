npm init -y -> to init empty node project with default values

npm install typescript --save-dev -> saving as a dev dep because we are shipping javascript - ts is just glorified linter

npx tsc --init -> to generate empty tsconfig file

npm install ts-node & ts-node-dev for dev development

add: "start": "ts-node-dev --respawn src/index.ts" for automatic typescript server restart on change

export not working this way