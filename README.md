# Rust API Test

## Requirements

- set project to nightly
    - rustup override set nightly (in project)
    - Add rocket = "0.4.7" to dependencies
    - cargo build

## Using Rocket

- Add #![feature(decl_marco)] flag to enable the unstable decl_marco feature

- Add #[marco_use] extern crate rocket;
    - This imports rocket or can: use rocket::*



