
# how to install
```
npm i -D @austenyte/tsconfig-bases
```

# available bases
- server(for node 12)

# example 
```
// tsconfig.json
{
    "extends": "@austenyte/tsconfig-bases/server/tsconfig.json",
    "compilerOptions": {
      "preserveConstEnums": true,
      "outDir": "./dist",
    },
    "include": ["src/**/*"],
    "exclude": ["node_modules", "**/*.spec.ts"]
}
```