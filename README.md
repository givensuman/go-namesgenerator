![go-namesgenerator logo](./assets/logo.png)

*What's in a name? That which we call a rose by any other name would smell as sweet*

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

## Utils

### `PascalCase(str string, normalize bool) string`
