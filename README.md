## Rust intro examples

### Code structure
Scripts are located at src/bin, as all of them needs to be executed separately

### How to run
Run the following code to compile file with specific name:
```cmd
cargo run --bin filename
```
Code above returns result with some metadata, to return only script result pass -q flag as below:
```cmd
cargo run -q --bin filename
```
### Cannot compile
Remember to run scripts C++ compiler is needed as MinGw