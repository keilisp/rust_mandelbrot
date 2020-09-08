# Rust Mandelbrot set

# Description

Basic singlethreaded implementation of Mandelbrot set in Rust

# Installation

Clone the repo into your folder

```sh
cd *your-folder*
git clone https://github.com/mediocreeee/rust_mandelbrot.git
```

Install all required packages via cargo

```sh
cargo build
```

# Usage

```sh
Usage:
target/debug/maldebrot FILE PIXELS UPPERLEFT LOWERRIGHT

Example:
target/debug/maldebrot mndel.png 1000x750 -1.20,0.35 -1,0.20
```
