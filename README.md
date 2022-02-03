![RustLogo](https://www.rust-lang.org/logos/rust-logo-128x128.png)
<!--TODO: Add R -> BF-->
# Rust Brainfuck interpreter

A brainfuck interpreter written in Rust. Fast and simple.

## Usage

```bash
bf file.bf
```

## Download
Download the interpreter [here](), or compile the compiler yourself 
for your own system using `cargo build --release`.

Then, either run it using `./bf`, or copy it to `/usr/local/bin` folder (or make a symlink).

<details>
  <summary>Click for full instructions in making a symlink to /usr/local/bin</summary>
    
**Linux & MacOS**
```bash
# Go to /usr/local/bin folder
cd /usr/local/bin

# Make a symlink
ln -s /path/to/bf bf

# Or, alternatively, move the binary to the folder
mv /path/to/bf bf
```

**Windows**
```PowerShell
CD \Windows\System32
mklink bf \path\to\bf
```
*NOTE: I have no experiene with Windows PowerShell, so do correct me if I'm wrong.*
</details>