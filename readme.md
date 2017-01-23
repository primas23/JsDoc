# Adding documentation via jsdoc

## Build the documentation
1. You need to:
```
npm install
```

2. If you want the defaul template:
```
npm run jsdoc
```

3. If you want the bootstrap template:
```
npm run jsdocbootstrap
```

## Configuration

1. JavaScript files to build configuration are placed in the conf.json (configuration file for the jsdoc).
```
"include": [
            "index.js",
            ...,
            ...
        ],
```