# This is a demo using ES6 and bebel

### How to use it
```
    npm install
    npm start
```

### about app.js
```
    You can write code with ES6 in app.js
```

### About concrete step using babel to translate

#### step one: make a new file .babelrc，this set up presets and plugins
```
{
    "presets": ["es2015", "stage-3"],
    "plugins": [
        "transform-runtime"
    ]
}
```

### step two: install presets and plugins
```
    npm install babel-preset-es2015 babel-presets-stage-3 --save-dev
    npm install babel-plugin-transform-runtime --save
```

### step three: install babel-watch module which can resume application when some file been modified
```
    npm install babel-watch --save-dev
    npm install babel-runtime --save
```

### step four: instal babel instrument
```
    npm install bebel-cli -g
```
