
# [Predawn](https://jamiewilson.io/predawn) for [HyperTerm](https://hyperterm.org/)

![Screenshot of Predawn for Hyperterm](https://i.imgur.com/crOzaqr.png)

## Installation

Add to the `plugins` array in your `.hyperterm.js` file:

```js
module.exports = {

  config: { /* ... */ },

  plugins: [
    "predawn-hyperterm"
  ]

};
```

## Overwrite default font family

```js
module.exports = {
  config: {
    /* ... */
      predawn: {
        fontFamily: 'Hasklig, "Source Code Pro", monospace',
      }
    /* ... */
  }
}
```
