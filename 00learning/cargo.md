
Cargo is Rust’s build system and package manager. Most Rustaceans use this tool to manage their Rust projects because Cargo handles a lot of tasks for you, such as building your code, downloading the libraries your code depends on, and building those libraries

`cargo --version`

### Creating a project
`cargo new learningrust`

### DO NOT generate .gitfiles
`cargo new  --vcs=git`

### Building and running Cargo Project
`cd <cargo project>`
run the command:
`cargo build`

run the project:
`cargo run` 

### Cargo Check: to check the code

Cargo also provides a command called `cargo check`. This command quickly checks your code to make sure it compiles but doesn’t produce an executable

### preparing for release
`$ git clone example.org/someproject`
`$ cd someproject`
`$ cargo build`


