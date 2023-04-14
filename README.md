
# cargo-use

Cargo subcommand to start a new Rust project from a boilerplate/template repository.


## Prequisites

- `git`
## Installation

Install cargo-use with cargo

```bash
cargo install cargo-use
```
    
## Usage

```bash
cargo use <username>/<repo-name>
```

Default:
```bash
cargo use i4o-dev/startrs
```

Custom project name:
```bash
cargo use i4o-dev/startrs --name test-project
```

With additional dependencies:
```bash
cargo use i4o-dev/startrs --with tokio axum
```

Initialize git repo:
```bash
cargo use i4o-dev/startrs --gitinit true
```
