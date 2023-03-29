[![Crates.io](https://img.shields.io/crates/v/roli.svg)](https://crates.io/crates/roli)
[![Documentation](https://docs.rs/roli/badge.svg)](https://docs.rs/roli/)
[![dependency status](https://deps.rs/repo/github/chloe-woahie/roli/status.svg)](https://deps.rs/repo/github/chloe-woahie/roli)


# roli

A low level api wrapper for Rolimons.com.

# Notes

* This crate is a low level wrapper due to the fact that allowed requests to the website are limited. To maintain flexibiliy while also using the endpoints responsibly, the user is expected to maintain their own caching.

# API Coverage Checklist
- [x] Items API
- [x] Deals API
- [x] Trade Ad API
- [x] Player API
- [x] Game API
- [x] Groups API
- [x] Market Activity API

# Contributing
Pull requests are welcome!

Note that all public functions are required to make exactly one request to Rolimons.com.

# License
MIT License
