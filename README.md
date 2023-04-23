## Tech
- [sqlc](https://docs.sqlc.dev/en/latest/overview/install.html)
- [go_migrate](https://github.com/golang-migrate/migrate)

## Aditional Configs
To use tiktoken-go lib, you must to go to tiktoken-go repository and to compile /tiktoken-cffi folder with rust lang:

```
~/dev/tiktoken-go/tiktoken-cffi$ cargo build --release
```

The file generated is libtiktoken.a
