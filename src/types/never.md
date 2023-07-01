# Never type

> **<sup>Syntax</sup>**\
> _NeverType_ : `!`

The never type `!` is a type with no values, representing the result of
computations that never complete. Expressions of type `!` can be coerced into
any other type. 

The `!` type can **only** appear in function return types presently.

```rust
extern "C" {
    pub fn abort() -> !;
}
```
