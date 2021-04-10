# Rustのメモ

Rustの日本語ドキュメントのうち、The Rust Programming Language の和訳をすすめてみる

- https://doc.rust-jp.rs/

## 1

### 1.2 helloworld

- rustc : Rustのコンパイラっぽい
- AOT(Ahead-Of-Time)コンパイル言語: 予めコンパイルしておく

### 1.3 Hello Cargo

- `cargo new hoge_project` でプロジェクト生成
- ビルド結果は `target/debug` に生成される

- cargo build
  - ビルドのみ
- cargo run
  - ビルド+実行
- cargo check
  - 実行ファイルは生成せず、コンパイルエラーがないかのチェック。dry run?

- cargo build --release
  - リリースビルド `target/release`

