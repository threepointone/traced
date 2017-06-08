traced
---

```jsx
let svg = trace`
–▀██▀─▄███▄─▀██─██▀██▀▀▀█─
──██─███─███─██─██─██▄█───
──██─▀██▄██▀─▀█▄█▀─██▀█───
─▄██▄▄█▀▀▀─────▀──▄██▄▄▄█

` // returns jsx form of svg tag

// ... and in your render function somewhere 

<div>{svg}</div>  

// etc etc 
```

- uses potrace behind the scenes, pass custom options with 
```jsx
let svg = traced(options)`

`
```