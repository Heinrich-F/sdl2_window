# sdl2_window [![Build Status](https://travis-ci.org/PistonDevelopers/sdl2_window.svg?branch=master)](https://travis-ci.org/PistonDevelopers/sdl2_window) [![Crates.io](https://img.shields.io/crates/v/pistoncore-sdl2_window.svg)](https://crates.io/crates/pistoncore-sdl2_window) [![Crates.io](https://img.shields.io/crates/l/pistoncore-sdl2_window.svg)](https://github.com/PistonDevelopers/sdl2_window/blob/master/LICENSE)

An SDL2 back-end for the Piston game engine

Maintainers: @TyOverby, @bvssvni, @Coeuvre, @mitchmindtree

[How to contribute](https://github.com/PistonDevelopers/piston/blob/master/CONTRIBUTING.md)



# Installation
 To use this as a dependency, add the following code to your Cargo.toml file:

```rust
    [dependencies.pistoncore-sdl2_window]
    git = "https://github.com/PistonDevelopers/sdl2_window"
```


### How to create a window

```Rust
let mut window: Sdl2Window = WindowSettings::new("SDL Window", (640, 480))
    .fullscreen(false)
    .vsync(true)
    .build()
    .unwrap();
```

See the examples for more ways to create a window.

### Troubleshooting

* [I get `ld: library not found for -lSDL2` error on OSX](https://github.com/PistonDevelopers/rust-empty/issues/175)

## Dependencies

![dependencies](./Cargo.png)

