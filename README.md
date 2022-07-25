# go-preact

>  `go-preact` is a template to create portable server apps with preact frontend in a single binary executable.

## Usage

```sh
# build
make

# build frontend
make build-preact

# build the executable
make build-go

# run the binary
bin/preact
```

## Notes

- Change binary name in the `Makefile`
- Change app name in `package.json` and `package-lock.json` and `src/manifest.json`