## Last Week's Accomplishments
Rewrote most of the C code to Rust, calls the perf\_event\_open syscall
directly from Rust. Still buggy so not merged yet. Commited to branch b7777.

## This Week's Plan
Write the presentation for large group

## Anything Blocking?
Basically the same as last week:
Rust is funny about structs with bitfields, so we'll see how that goes.
Currently empty strings use fewer instructions to compare, and end up being the largest outlyer. This creates false positives which completly ruin results.

## Notes
N/A
