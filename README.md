# unnamed WASM-4 Jam #2 entry game repository

A game written in [Nelua](https://nelua.io/) for the [WASM-4](https://wasm4.org) fantasy console.

Entry for [WASM-4 Jam #2](https://itch.io/jam/wasm4-v2).

## Dependencies

Install [Nelua](https://nelua.io/installing/) language, then make [WASM-4](https://wasm4.org/docs/getting-started/setup) fantasy console and [WASI SDK](https://github.com/WebAssembly/wasi-sdk#install) available.

## Building

Build the cart by running:

```shell
make
```

Then run it with:

```shell
w4 run build/cart.wasm
```

## License

This game is licensed under [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), see the `LICENSE` file.
