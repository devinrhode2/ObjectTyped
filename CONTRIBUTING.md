Created with:

- node 16.8.0
- npm v7.21.1
- yarn 1.22.11

And:

```
npx tsdx create ObjectTyped
```

On Monday August 30th CST 12:20pm

Used tsdx cause I don't want to wonder if I've properly created a ts library.
Likely it's 90% cruft but I don't know.
Hopefully end-users npm install is very fast.

Maybe one day this package will be updated to remove the `as` assertions, and add `@deprecated` tags indicating people can uninstall this package.

Unsurprisingly, eslint has some issue:

```
ObjectTyped ➤ yarn lint

yarn run v1.22.11
$ tsdx lint
Defaulting to "tsdx lint src"
You can override this in the package.json scripts, like "lint": "tsdx lint src otherDir"

/Users/Devin.Rhode/pss/ObjectTyped/src/index.ts
  0:0  error  Parsing error: Cannot read property 'map' of undefined

✖ 1 problem (1 error, 0 warnings)

error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

I'm not really worried about this.
