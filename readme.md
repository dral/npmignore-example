# npmignore example

file structure
```
.npmignore
bar/index.js
baz/index.js
foo/index.js
   /.npmignore
```

the root `.npmignore` removes only the `baz` directory.
the nested `foo/.npmignore` removes all content (from this point on).
