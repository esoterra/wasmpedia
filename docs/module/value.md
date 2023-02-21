[Functions]: ./function.md
[Instructions]: ./instructions.md

# Value (Module)

Wasm Modules operate on primitive values (e.g. 32-bit integers) which [Functions] and [Instructions] take in and return.

These values can exist on the stack, in locals and globals, and be loaded and stored from linear memory. Wasm doesn't have values that are smaller than 32 bits, **but** you are able to perform 8 and 16 bit loads and stores.

The main kinds of types are

* [Integers](#integers)
* [Floating Point Numbers](#floating-point-numbers)

## Integers

Wasm has three kinds of integer types that correspond to the name prefix.

* `i` - An integer that can be either signed or unsigned
* `u` - An unsigned integer
* `s` - A signed integer

For each of these kinds of integers there are 32 and 64 bit variants.

| Name | Description |
| ---- | ----------- |
| `i32` | A 32-bit integer that has unknown signedness
| `u32` | An unsigned 32-bit integer
| `s32` | A signed 32-bit integer
| `i64` | A 64-bit integer that has unknown signedness
| `u64` | An unsigned 64-bit integer
| `s64` | A signed 64-bit integer

## Floating Point Numbers

Wasm has 32 and 64 bit floating point numbers.

| Name | Description |
| ---- | ----------- |
| `f32` | A 32-bit floating point number
| `f64` | A 64-bit floating point number