
# Mostly adequate guide to GrainLang

## Introduction

## Setup

## We always need a "Hello World"

"Hello World" is the best way to check your setup. Create a file named `hello-world.gr` with the below source code:

```grain
/* Hello world with Grain */

print("👋 Hello World 🌍")
```

Then:

- Compile it: `grain compile hello-world.gr` (it will generate a new file: `grain run hello-world.gr.wasm`)
- Run it: `grain run hello-world.gr.wasm`

You should get an amazing and lovely message: `"👋 Hello World 🌍"`

> **Remark**: If you installed [wasmtime](), you can execute the wasm file like this: `wasmtime hello-world.gr.wasm`

> **How to install WasmTime**:
> ```bash
> curl https://wasmtime.dev/install.sh -sSf | bash
> ```


## Variables
## Functions

