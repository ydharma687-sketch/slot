# Sharp-Shimmerless changes adapted to slot-main

This archive contains files modified against the supplied `slot-main.zip` baseline.
Copy/extract the archive into the root of your main-branch checkout, preserving paths.

Included changes:
- Adds Sharp and Sharp Grid shader effects and persistence names.
- Adds Quick Menu options and toast labels.
- Adds app/frontend mappings while retaining the main branch's other code.
- Preserves the main branch's current footer/screen-layout code in `pipeline.rs`.

Validation:
- The merge was prepared against the supplied main-branch ZIP.
- Compilation and tests were NOT run because Cargo is unavailable in the editing environment.
- Run `cargo test --workspace` and `cargo build --release` in your own workflow.
