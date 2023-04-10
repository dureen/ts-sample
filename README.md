# ts-sample
## Installation
```
$ npm install typescript --save-dev
```
> added 1 package in 14s

```
$ npx tsc
```
> Version 5.0.4\
```
$ tsc: The TypeScript Compiler - Version 5.0.4\
```

## Configure the Compiler
```
$ npx tsc --init
```
Edit file `tsconfig.json` and then add these line:
```json
{
  "include": ["src"],
  "compilerOptions": {
    "outDir": "./build"
  }
}
```
Edit file `package.json` and add line:
```json
{
  ...  
  "scripts": {
    "build": "npx tsc",
    "watch": "npx tsc -w -p ."
  },
  ...
}  
```
Run compiler:
```
$ npm run build 
```
or
```
$ npm run watch 
```
## Enjoy your coding!
