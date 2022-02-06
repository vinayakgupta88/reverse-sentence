# reverse-sentence

Reverse the words of a sentence.

## Install
```sh
npm install @vinayakgupta88/reverse-sentence
```

## API

```js
require("reverse-sentence") => Function
reverse(sentence) => String
```

## Example
```js
const reverseSentence = require("reverse-sentence");

const sentence = "Hello Vinayak!";

const reversed = reverseSentence(sentence);

console.log(reversed) // Vinayak! Hello
```
