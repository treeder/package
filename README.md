# package

Template for building a JavaScript package in minutes. 

## Features

- Just fill in the blanks and people can start using it.
- Automatically bumps version every commit to main

## Getting started

- Create a new repository using this as a template.
- Fill in index.js with exports.

Then when ready, people can just:

```sh
npm install yourorg/yourrepo
```

Or from CDN:

```js
import { yourExport } from 'https://cdn.jsdelivr.net/gh/yourorg/yourrepo@9/'
```

## Testing

Add more tests to [test/test.js], super easy. Uses [TestKit](https://github.com/treeder/testkit).