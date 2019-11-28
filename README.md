# Spectral MP Core

## Description
Core library for the SpectralMP tool.

Contains the (csv) files parsing, data smoothing and marker point detection algorithms.

## Development notes

### Installation and path
We prefer a local installation of typescript
```sh
npm init -y
npm install --save-dev typescript
```

To extend the path:
* zsh `path+=$(realpath node_modules/.bin)`
* bash `export PATH="./node_modules/.bin:${PATH}"`

### Configuration
We want to have at least ES6 supports, so we can easily use thing like `Number.isInteger` without polyfile or transpiler.
See `tsconfig`.
```sh
tsc --init --rootDir src --outDir build --target ES6 --module ES6 --noImplicitAny true
mkdir src
```


