# Fake API

Fake API with custom images. To be used on projects for The Odin Project curriculum.

## Example usage

```js
fetch(
  "https://trithereon.github.io/fake-api/api/v1/shopping-cart-products.json",
)
  .then((res) => res.json())
  .then((json) => console.log(json));
```

Response will be the entire json, which can be parsed and manipulated by the user.
