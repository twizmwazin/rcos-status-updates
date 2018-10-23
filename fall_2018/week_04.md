## Last Week's Accomplishments
Implemented bindgen suport for perf\_event.h.

## This Week's Plan
Move the b77 function to Rust. This will be done in a few steps, first moving
declarations to rust and passing them to C, then hopefully moving the logic to
Rust.

## Anything Blocking?
Rust is funny about structs with bitfields, so we'll see how that goes.

## Notes
N/A
