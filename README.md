# OS Development in Rust

This repository contains the code base for developing our own operating system kernel using Rust. The goal is to create a Rust executable that can run on the bare metal without relying on an underlying operating system.

## Blog

This project is being developed openly on GitHub. If you encounter any issues or have questions, please feel free to open an issue on the repository. You can also leave comments at the bottom of the blog post.

The blog you're following is [Operating System Development in Rust](https://os.phil-opp.com/). It provides detailed explanations and tutorials on OS development using Rust.

## Learning Progress

As a student following the blog, you'll be learning the following topics in OS development using Rust:

- Disabling the Standard Library
  - The `no_std` Attribute
  - Panic Implementation
  - The `eh_personality` Language Item
  - Disabling Unwinding
- Overwriting the Entry Point
- Linker Errors
- A Minimal Rust Kernel

Please refer to the blog posts on [Operating System Development in Rust](https://os.phil-opp.com/) and the source code in this repository to gain a better understanding of each topic.

## Repository Structure

The repository structure is as follows:

- `Cargo.toml` and `Cargo.lock`: Dependency and build configuration files for the Rust project.
- `src`: Directory containing the source code of the operating system.
- `x86_64-os.json`: Configuration file for the Rust target specification.

Feel free to explore the source code and modify it as you progress through your OS development journey.

