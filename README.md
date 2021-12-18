# Minigrep

An example command line application in Rust.
Built using the [minigrep](https://doc.rust-lang.org/book/ch12-00-an-io-project.html) tutorial

## Steps

- add `std::env::args` to read command line arguments
- use index 1+ for args since index 0 is program name
- read file with `std::fs`
- extract args to struct
- add error handling with Result
- add search with test
- check env var with `env::var`
- add search case insensitive with test
