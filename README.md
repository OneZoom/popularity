# popularity

This repository contains a refactoring of the identifier mapping code in the main OneZoom repository

We assume that you have populated the `OZprivate` directory herein with a `data` directory, identical to (or symlinked to) the [OneZoom/OZtree/OZprivate/data](https://github.com/OneZoom/OZtree/tree/master/OZprivate/data) directory, containing, for instance a `Wiki` folder populated with the [correct files](https://github.com/OneZoom/OZtree/tree/master/OZprivate/data/Wiki).

If you are on a unix-like system, and your [OZtree github clone](https://github.com/OneZoom/OZtree) is in the same parent directory as this repository, you can simply symlink them using e.g. 

```
ln -s ../OZtree/OZprivate/data ./OZprivate/
```