# Rust-IT8951
Rust-based driver for the Waveshare IT8951 e-ink board.

This library provides hardware abstractions so that the same library can be used in three different ways:
- The library can be run on a Raspberry Pi to interface with a connected IT8951 board
- The library can be run on a PC to connect to a IT8951 via a [Bus Pirate](https://www.sparkfun.com/products/12942) using SPI
- The library emulates the IT8951 hardware so that the higher-level operations can be debugged and tested without an actual IT8951 board

See [buspirate_it8951.md](buspirate_it8951.md) for a guide on how to use a Bus Pirate with the Waveshare IT8951 board.