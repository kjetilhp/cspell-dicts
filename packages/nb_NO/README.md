# Cspell Norwegian Dictionary

Norwegian dictionary for cspell.

Dictionary files copied from the LibreOffice repo

## Installation

Global Install and add to cspell global settings.

```sh
npm install -g cspell-dict-nb-no
cspell-dict-nb-no-link
```

## Uninstall from cspell

```sh
cspell-dict-nb-no-unlink
```

## Manual Installation

The `cspell-ext.json` file in this package should be added to the import section in your cspell.json file.

```javascript
{
    // …
    "import": ["<path to node_modules>/cspell-dict-nb-no/cspell-ext.json"],
    // …
}
```

## Building

Building is only necessary if you want to modify the contents of the dictionary. Note: Building will take a few minutes for large files.

```sh
npm run build
```

## Contributors

- [Kjetil Paulsen](https://github.com/kjetilhp)

## License

This package is licensed under MIT

The dictionary is licensed under the following licenses. See LICENSE for more
GNU GPL version 2.0
