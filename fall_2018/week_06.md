## Last Week's Accomplishments
Implemented log level support to be able to more easily add debug/trace messages
Ran tools like rust-clippy to clean up non-idiomatic Rust code.

## This Week's Plan
Try and convert remaining C code to Rust.
Fix outlyer calculation favoring empty strings for ascii input.

## Anything Blocking?
Rust is funny about structs with bitfields, so we'll see how that goes.
Currently empty strings use fewer instructions to compare, and end up being the largest outlyer. This creates false positives which completly ruin results.

## Notes
N/A
