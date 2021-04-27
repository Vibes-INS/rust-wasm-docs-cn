# 教程：康威生命游戏
这是一个教程，在 Rust 和 WebAssembly 上实现[康威生命游戏](https://zh.wikipedia.org/wiki/康威生命游戏)。

## 这个教程是给谁的？
本教程是为那些已经有了基本的 Rust 和 JavaScript 经验，并且希望学习如何将 Rust、WebAssembly 和 JavaScript 结合使用的人编写的。
你需要能够阅读和编写基本的 Rust、JavaScript 和 HTML，但是不用精通它们。

## 我将学到什么？
- 如何设置用于编译到WebAssembly的Rust工具链。
- 用于开发由 Rust、WebAssembly、JavaScript、HTML 和CSS组成的多语言程序的工作流。
- 如何设计api以最大限度地利用 Rust 和 WebAssembly 的优点以及 JavaScript 的优点。
- 如何调试从 Rust 编译的 WebAssembly 模块。
- 如何时间配置文件 Rust 和 WebAssembly 程序，使他们更快。
- 如何调整 profile Rust 和 WebAssembly 程序的大小，使 `.wasm` 二进制文件更小，通过网络下载更快。