# dt-retag
Refresh tags on all DT-published packages in the @types scope.

Run this whenever a new version of Typescript is released.

1. `--dry` will not actually do the retag, but print what it would do.
2. `--name=X` will only retag ONE package, and is optional. This is only needed to fix types-publishers' mistakes, or to unwedge it after its cache is corrupted.

Normal usage is just `node index.js`.
Make sure that you have an up-to-date Definitely Typed repo next to the dt-retag directory.
