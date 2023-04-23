## Tech
- [sqlc](https://docs.sqlc.dev/en/latest/overview/install.html)
- [go_migrate](https://github.com/golang-migrate/migrate)

## Aditional Configs
### Tiktoken-Go
To use tiktoken-go lib, you must to go to tiktoken-go repository and to compile /tiktoken-cffi folder with rust lang:

```
~/dev/tiktoken-go/tiktoken-cffi$ cargo build --release
```

The file generated is libtiktoken.a
### Go Migrate
You can download and to use CLI on your own machine, but you may change commands in this Makefile, switch ./migrate to migrate.
In this repo I use migrate file from [migrate repository](https://github.com/golang-migrate/migrate/tree/master/cmd/migrate), see [migrate release downloads](https://github.com/golang-migrate/migrate/releases) to get binaries file from your system and arch
