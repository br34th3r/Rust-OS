# Rust Operating System

An OS written entirely in Rust. It was a follow along with Phillipp Oppermann's blog post series on developing an OS in Rust.

It builds to a bootimage that can be run on hardware or via QEMU to display some basic text using the println macro in the `main.rs` file. It can also panic and point panics to the correct area. All of this thanks to the use of VGA Text Encoding and display in the `vga_buffer.rs` file written from scratch also based on the tutorial.
