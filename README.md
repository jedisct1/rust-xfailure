# xfailure

The `bail!` macro from the `failure` crate doesn't behave in an
intuitive way, and returns a string instead of the actual error.

This situation may change in the future. Meanwhile, this trivial crate
provides an `xbail!` macro that acts like `error_chain`'s `bail!` macro.

`xfailure` is also available on crates.io.
