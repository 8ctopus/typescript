# playing with typescript

## simple

```sh
npm install --save-dev typescript

# compile typescript into javascript without config file
npx tsc src/index.ts

# create typescript config file
npx tsc --init

# compile what's in config file into javascript
npx tsc
```

## more advanced using webpack

```sh
npm install --save-dev webpack webpack-cli typescript ts-loader

# convert typescript to javascript
npx webpack

# continously convert typescript to javascript
npx webpack watch

# start development server and watch changes
npm install --save-dev webpack-dev-server
npx webpack serve
```

https://www.fatalerrors.org/a/typescript-super-detailed-introduction.html
