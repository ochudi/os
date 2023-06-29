# OS Development in Rust

This repository contains the code base for developing our own operating system kernel using Rust. The goal is to create a Rust executable that can run on the bare metal without relying on an underlying operating system.

## Blog

This project is being developed openly on GitHub. If you encounter any issues or have questions, please feel free to open an issue on the repository. You can also leave comments at the bottom of the blog post.

## Source Code

The complete source code for this project can be found in the `post-01` branch of this repository. Make sure to switch to the appropriate branch to access the code relevant to the blog post.

## Table of Contents

- [Introduction](#introduction)
- [Disabling the Standard Library](#disabling-the-standard-library)
  - [The `no_std` Attribute](#the-no_std-attribute)
  - [Panic Implementation](#panic-implementation)
  - [The `eh_personality` Language Item](#the-eh_personality-language-item)
  - [Disabling Unwinding](#disabling-unwinding)
- [Overwriting the Entry Point](#overwriting-the-entry-point)
- [Linker Errors](#linker-errors)
