# Pug Plugin Mixin Output

## Captures the output of a mixin into a JS variable.

### How to use:

```pug
- const output = +someMixin(arg1, arg2, arg3)

.output-container
    != output
```


### Installation:
```js
import pugMixinOutput from 'pug-mixin-output';

// Then add the plugin to the pug options plugin section.
const options = {
    plugins: [
        pugMixinOutput,
    ]
}

pug.compile('string of pug', options);
```

[See Pug Reference](https://pugjs.org/api/reference.html)