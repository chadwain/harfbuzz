# harfbuzz

This is [harfbuzz](https://harfbuzz.github.io/) packaged for [Zig](https://ziglang.org/).

I've had to fork this project from [allyourcodebase/harfbuzz](https://github.com/allyourcodebase/harfbuzz) because:
* It and its dependencies were using old package hashes (before zig 0.14.0)
* It didn't work on Windows due to [this issue](https://github.com/ziglang/zig/issues/17652)
