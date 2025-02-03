# Dangling Pointer in Rust Vector

This repository demonstrates a common error in Rust involving dangling pointers and vector modifications. The code in `bug.rs` showcases how creating a reference to a vector element, and then modifying the vector (e.g., adding elements) can lead to a dangling pointer, resulting in undefined behavior. The corrected version in `bugSolution.rs` addresses this issue, ensuring memory safety.

## How to Reproduce

1. Clone this repository.
2. Run `rustc bug.rs` and `cargo run` to see the potential error. 
3. Run `rustc bugSolution.rs` and `cargo run` to observe the correct and safe way to handle vector references.