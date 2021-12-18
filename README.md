# Minigrep

An example command line application in Rust

## Steps

- add `std::env::args` to read command line arguments
- use index 1+ for args since index 0 is program name
- read file with `std::fs`
- extract args to struct
- add error handling with Result
- add search with test
- check env var with `env::var`
- add search case insensitive with test
