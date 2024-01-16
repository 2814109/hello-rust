# hello-rust

## view binary file

```
hexdump -C target/debug/hello-rust
```

or

```
hexdump -C target/debug/hello-rust | less
```

## check file

```
cat src/main.rs
```

## knowledge

- libc : 一般には「標準 C ライブラリ」の短縮表現として 使われている
- command:hexdump : ファイルを 8 進数や 16 進数でダンプする
