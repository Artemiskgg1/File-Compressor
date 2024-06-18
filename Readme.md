# Gzip Compression Tool

This Rust program compresses a specified file using gzip compression and writes the compressed data to a target file. It provides information about the size of the source and target files and the time taken for the compression process.

## Requirements

- Rust (latest stable version recommended)
- `flate2` crate

## Installation

1. Install Rust by following the instructions at [rust-lang.org](https://www.rust-lang.org/learn/get-started).
2. Add the `flate2` crate to your `Cargo.toml`:
   ```toml
   [dependencies]
   flate2 = "1.0.24"
   ```

## Usage

1. Clone this repository or download the source code.
2. Navigate to the project directory.
3. Build the project:
   ```sh
   cargo build --release
   ```
4. Run the program with the source and target file paths as arguments:
   ```sh
   cargo run --release source_file target_file
   ```

### Example

```sh
cargo run --release input.txt output.gz
```
