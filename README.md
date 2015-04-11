# go-env-sh

Print out `go env` with just shell.


why? because I need to write tools that install go probuilt binaries for the right architecture. So that this just works on _any_ machine:

```
./ipfs-install.sh
```

Usage:

- `go-env` (will be) an env
- `go-platform` will output `$GOOS-$GOARCH`
