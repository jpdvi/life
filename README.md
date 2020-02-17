# WASM-game-of-life

My implementation of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) using web assembly from the rustwasm [book](https://rustwasm.github.io/docs/book/game-of-life/rules.html).

## Usage

Requires `wasm-pack` and `npm` to be installed.

### Run the project

```sh
wasm-pack build && cd www && npm run start
```

Then navigate to `localhost:8080` in your browser. 

## Examples

![](https://storage.googleapis.com/jpdvi-public/wasm.gif)
