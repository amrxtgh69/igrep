# igrep

A tiny grep clone written in Rust. Searches for a query string in a file and prints matching lines.

## Usage

```
cargo run -- <query> <file_path>
```

For case-insensitive search:

```
IGNORE_CASE=1 cargo run -- <query> <file_path>
```

## Example

```
cargo run -- duct poem.txt
```

## Tests

```
cargo test
```
