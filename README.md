### opn
---
https://github.com/sindresorhus/opn

```
npm install opn
```

```js
const opn = require('opn');

opn('unicorn.png').then(() => {
});

opn('http://sindresorhus.com');

opn('http://sindresorhus.com', {app: 'firefox'});

opn('http://sindresorhus.com', {app: ['google chrome', '--incognito']});

```

```
```


