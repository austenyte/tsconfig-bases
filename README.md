
# how to install
```
npm i -D @austenyte/tsconfig-bases
```

# available bases
- node 12

# example 
```
// tsconfig.json
{
    "extends": "@austenyte/tsconfig-bases/node12.json",
    "compilerOptions": {
      "preserveConstEnums": true,
      "outDir": "./dist",
    },
    "include": ["src/**/*"],
    "exclude": ["node_modules", "**/*.spec.ts"]
}
```

# Reference
1. https://node.green/
