# Quick Intro to Rust

* [rust-lang.org](https://www.rust-lang.org/)
* [Install](https://www.rust-lang.org/tools/install)
  * `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh` for linux like systems.
  * **rustup** to manage the toolchain.
    * `rustup self uninstall` to uninstall it.
    * `rustup doc` to read local document in a web browser.
  * **rustc** is the compiler.
    * try `rustc simple.rs`
    * or `echo 'fn main(){println!("test");}'|rustc -o ss - && ./ss`
  * **cargo** is the management command.
    * `cargo new hello_world`
    * `cd hello_world`
    * `cargo build` or `cargo run`
  
* Learn: https://www.rust-lang.org/learn
* [evcxr](https://github.com/evcxr/evcxr): Rust jupyter kernel 
  * `cargo install --locked evcxr_jupter`
  * `evcxr_jupyter --install`