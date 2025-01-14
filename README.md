This repository demonstrates a common, subtle bug in Rust: data races caused by multiple mutable references to the same variable. The `bug.rs` file shows the buggy code, which leads to unpredictable results. The `bugSolution.rs` file demonstrates the correct way to handle mutable references in this situation, avoiding the data race.