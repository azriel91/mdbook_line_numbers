# Setup

## Add this to `book.toml`

```toml
[output.html]
additional-js = ["js/highlightjs-line-numbers.js"]
# or
# additional-js = ["js/highlightjs-line-numbers.min.js"]
```

## Create the file

```bash
mkdir js
```

Copy one of the following into the directory:

<details><summary>Non-minified: <code>highlightjs-line-numbers.js</code></summary>

```js
{{#include ../js/highlightjs-line-numbers.js}}
```

</details>

<details><summary>Minified: <code>highlightjs-line-numbers.min.js</code></summary>

```js
{{#include ../js/highlightjs-line-numbers.min.js}}
```

</details>
