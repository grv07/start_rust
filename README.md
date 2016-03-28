#Hello world in rust.

1. Install Rust:

    curl -sSf https://static.rust-lang.org/rustup.sh | sh

2. If we've got Rust installed, we can open up a shell, and type this:

    $ rustc --version

Cargo is Rust’s build system and package manager,and Rustaceans use Cargo to manage their Rust projects
As the vast, vast majority of Rust projects use Cargo, we will assume that you’re using it for the rest of the book. Cargo comes installed with Rust itself, if you used the official installers. If you installed Rust through some other means, you can check if you have Cargo installed by typing:

    $ cargo --version

3.To start a new project with Cargo, enter cargo new at the command line:

    $ cargo new hello_world --bin

4.Now just run hello word:

    $ cargo run

For more follow https://doc.rust-lang.org/book/getting-started.html
