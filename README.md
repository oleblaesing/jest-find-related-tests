# jest-find-related-tests

You just have to install the dependencies first:

```sh
npm i
```

You can now run

`npm run find` for `jest --findRelatedTests`

and

`npm run watch` for `jest --watch`.

If you edit `data.json` through altering the `messages` key, save the file and run `npm run watch`, it will automatically test `index.js`, because of its alteration.

But if you run `npm run find`, then there won't be any tests found.
