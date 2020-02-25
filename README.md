# Boxx

_note: this library is still in development and updates may contain breaking changes_

Display informational boxes in the terminal.

## Example

Your `Cargo.toml` should include `boxx` as a dependency

```toml
[dependencies]
boxx = "0.0.2-beta"
```

```rust
use boxx::Boxx;

fn main() {
  Boxx::default().display("Hello, World!");
}
```

More examples can be found [here](/examples).

## Acknowledgements

This library was heavily inspired by [boxen](https://npmjs.com/package/boxen), but has no official association with that project.
