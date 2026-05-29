![go-namesgenerator logo](./assets/logo.png)

*What's in a name? That which we call a rose by any other name would smell as sweet.*

# go-namesgenerator

This is a modified equivalent to [moby/moby/namesgenerator](https://pkg.go.dev/github.com/docker/docker@v28.5.2+incompatible/pkg/namesgenerator) which has been deprecated.

## Install

```bash
go get github.com/givensuman/go-namesgenerator
```

Import:

```go
import (
  "github.com/givensuman/go-namesgenerator"
)
```

## Usage

```go
// GetRandomName generates a random name from the list of adjectives and animals in this package
// formatted as "adjective_animal". For example 'focused_squirrel'. If retry is non-zero, a random
// integer between 0 and 10 will be added to the end of the name, e.g `focused_squirrel3`
func GetRandomName(retry int) string
```

## License

[MIT](./LICENSE)
