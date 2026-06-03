# lighting.js
This is a JavaScript library that makes coding easier and it made by TypeScript. This is also a frontend library. The JavaScript function are very simple at there.

## Features
The unique part is type safety, easier and no compilation.

1. Math functions 
2. makeEvent function
3. makeTag function
4. Selectors

## Math functions
```
// import math functions from lightingjs
import { light } from "lightingjs";

// the arguments are type, minimum and maximum number.
const num = light.randNum("int", 1, 15);

console.log(num);
```

## makeEvent function
```
// the arguments are element, event type, callback
makeEvent("#button", "click", () => {
  console.log("clicked!");
});
```

## makeTag function
```
// this function is easier Version of 'document.createElement()'
const box = makeTag("div", {
  text: "hello world", // inner text
  classes: ["box"] // add multiple class name
});

document.body.appendChild(box); // add in body
```

## Selectors
```
// query selector 
query(".box");

// id selector
id("box");
```

## Installation
```
npm i lightingjs
```

## CDNs 
```
<script src="https://unpkg.com/lightingjs"></script> 

// or 

<script src="https://cdn.jsdelivr.net/npm/lightingjs"></script>
```

## Update
```
npm update lightingjs
```

## Version
```
npm list lightingjs
```

