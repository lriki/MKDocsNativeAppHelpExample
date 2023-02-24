MKDocsNativeAppHelpExample
==========

Prerequisites
----------

### Install poetry

https://python-poetry.org/docs/

### Install packages

```sh
poetry install
npm install
```

Run mkdocs with poetry
----------

### Build

```
poetry run mkdocs build
```

### Serve

```
poetry run mkdocs serve
```

Run on NW.js
----------

### Run test

Display the inside of the site folder with nwjs.

```sh
npm run dev
```

### Deploy

```sh
npm run build
```

The executable will be output in the `build` folder.

Run `docs.exe` to view the documentation.
