# Slint Rust Memory Match Tile Game

A game that's using [Slint](https://slint.rs) for the user interface.

## About

This is a simple Memory Match Tile Game used as an example of a Rust application with Slint as toolkit
for the user interface. It demonstrates the integration between the `.slint` UI markup and
Rust code, how to trigger react to callbacks, get and set properties and use basic widgets.

## Usage

1. Install Rust by following the [Rust Getting Started Guide](https://www.rust-lang.org/learn/get-started).
   Once this is done, you should have the ```rustc``` compiler and the ```cargo``` build system installed in your path.
2. Install [`cargo-generate`](https://github.com/cargo-generate/cargo-generate)
    ```
    cargo install cargo-generate
    ```
3. Set up this project
    ```
    cargo generate --git https://github.com/krons711/memory-game --name memory-game
    cd memory-game
    ```
3. Build with cargo
    ```
    cargo build
    ```
4. Run the application binary
     ```
     cargo run
     ```

You can load this project directly in [Visual Studio Code](https://code.visualstudio.com) and install [Slint extension](https://marketplace.visualstudio.com/items?itemName=Slint.slint).

## Slint documentation

To learn more about the Slint APIs and the `.slint` markup language check out [online documentation](https://slint.dev/docs).
