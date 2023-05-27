# Hello Cargo
This project serves as Cargo reference.
```bash
cargo --version
```
```bash
cargo new PROJECT_NAME
```
GIT files won’t be generated if you run `cargo new` within an existing GIT repository;
you can override this behavior by using `cargo new --vcs=[git|hg|pijul|fossil|none]`
NOTE: git is a common version control system;
you can change `cargo new` to use a different version control system or
no version-control-system by using:
```bash
cargo new PROJECT_NAME --vcs=none
```
```bash
cargo new LIB --lib
```
```bash
cargo add CRATE_NAME
cargo update
cargo update -p CRATE_NAME

cargo check
cargo build
cargo run

cargo check --release
cargo build --release
cargo run --release

cargo clean
cargo clean --release

cargo doc
cargo doc --open
cargo doc --release
cargo doc --release --open
```
