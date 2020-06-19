# restore-source-tree
Restores file structure from source map (only Webpack source map files supported)

## Usage

```sh
> npm i -g restore-source-tree

> restore-source-tree -n -o test 2333.js.map
```

### npm
```
npm -v
3.5.2

```
### restore-source-tree

```
Usage: restore-source-tree [options] <file>

Restores file structure from source map

Options:
  -V, --version               output the version number
  -o, --out-dir [dir]         Output directory ('output' by default) (default: "output")
  -n, --include-node-modules  Include source files in node_modules
  -h, --help                  output usage information

```
