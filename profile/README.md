## Bots.Garden 🤖🌼

Bots Garden is the house of various **[wasm](https://webassembly.org/)** and **[wasi](https://wasi.dev/)** experiments

The (most) active project of Bots Garden is **[Simplism](https://github.com/bots-garden/simplism)**: a cloud-native runtime for [Extism](https://extism.org/) **wasm** plug-ins.
> A tiny HTTP server for Extism wasm Plug-ins

Simplism is developed in Go with **[Wazero](https://wazero.io/)**[^1] as the Wasm runtime and **[Extism](https://extism.org/)**[^2], which offers a Wazero-based Go SDK and a Wasm plugin system.


There are two satellite projects of Simplism:

- [Simplism Builder](https://github.com/bots-garden/simplism-builder): a Docker Compose project bringing all the necessary tools to build WASM Extism plug-ins for Simplism.
- [Simplism IDE](https://github.com/bots-garden/simplism-ide): A "local cloud development environment" (with Docker Compose) to develop Extism plug-ins for Simplism without the need to install all the "complicated things".

## Blog posts

### Wazero

- Series: [Wazero, first steps](https://k33g.hashnode.dev/series/wazero-first-steps)
  - Wazero Cookbook - Part One: WASM function & Host application
  - Wazero Cookbook - Part Two: Host functions

### Extism

- Series: [Discovery of Extism (The Universal Plug-in System)](https://k33g.hashnode.dev/series/extism-discovery)
  - Extism & WebAssembly Plugins
  - Extism, WebAssembly Plugins & Host Functions
  - WebAssembly Plugin in JavaScript with Extism
  - Run Extism WebAssembly plugins from a Go application
  - Writing Wasm MicroServices with Node.js and Extism
  - Write a host function with the Extism Host SDK
  - Writing Host Functions in Go with Extism
  - Create a Webassembly plugin with Extism and Rust
  - WASM Microservices with Extism and Fiber
  - Extism Go SDK is now written on top of Wazero
- [Run WASM functions from Vert-x & Kotlin thanks to Extism](https://k33g.hashnode.dev/run-wasm-functions-from-vert-x-kotlin-thanks-to-extism)

### Simplism

- [Simplism, the straightforward way for a Wasm FaaS on Clever Cloud](https://k33g.hashnode.dev/simplism-faas-on-clever-cloud)
- [Deploy a wasm function on Koyeb in a blast with Simplism](https://k33g.hashnode.dev/deploy-a-wasm-function-on-koyeb-in-a-blast-with-simplism)

### Wasm - Wasi

- Series: [WASI and Node.js](https://k33g.hashnode.dev/series/wasi-nodejs)
  - WASI, first steps
  - WASI, Communication between Node.js and WASM modules with the WASM buffer memory
  - WASI, Communication between Node.js and WASM modules, another way, with STDIN and STDOUT



[^1]: Wazero is a project from **[Tetrate](https://tetrate.io/)**
[^2]: Extism is a project from **[Dylibso](https://dylibso.com/)**

