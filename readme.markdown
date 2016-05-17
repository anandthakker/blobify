# blobify

[webworkify](https://github.com/substack/webworkify) transforms `webworkify(require('...'))`
into `new Worker(URL.createObjectURL(new Blob([...source code...]), {type: 'text/javascript'}))`.  This is
almost identical to it, but ONLY gives the `Blob` part, not wrapped by `createObjectURL()` or `Worker()`.

# install

With [npm](https://npmjs.org) do:

```
npm install webworkify
```

# license

MIT
