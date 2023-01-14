# MiniGrep

MiniGrep is a simple grep clone written in Rust.

## Usage

```bash
cargo run -- <query> <filename>
```

To do a case-insensitive search, set the `IGNORE_CASE` environment variable:

```bash
IGNORE_CASE=1 cargo run -- <query> <filename>
```

## Testing

```bash
cargo test
```

## Credits

This project is based on the [Rust Book](https://doc.rust-lang.org/book/ch12-00-an-io-project.html).
