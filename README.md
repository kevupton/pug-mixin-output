# Pug Plugin Mixin Output

## Captures the output of a mixin into a JS variable.

### How to use:

```pug
- const output = +someMixin(arg1, arg2, arg3)

.output-container
    != output
```