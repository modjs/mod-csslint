mod-csslint
===

Validate css files with csslint


## Usage

```js
module.exports = {
    plugins: {
        "csslint": "mod-csslint"
    },
    tasks: {
        "csslint": {
            src: "test.css"
        }
    }
};
```