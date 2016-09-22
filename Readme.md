# fs-
A module that contains both API and CLI

## install

```
npm install fs-
npm install fs- -g
```

## usage  

```js
import {writeFile, readFile} from 'fs-'

writeFile({name: 'foo.txt', data: 'barbarbar'})

readFile({name: 'foo.txt'})

```


## CLI
```bash
$ fs- -w foo -n bar.txt

$ fs- -r foo.txt
```

## license

MIT. Copyright (c) [viii](https://github.com/ncysatnaf).
