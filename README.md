# goarchext

[![Godoc](http://img.shields.io/badge/godoc-reference-blue.svg?style=flat)](https://godoc.org/github.com/shamsher31/goarchext)

List of Archive file extensions for Go

### How to install
```go
go get github.com/shamsher31/goarchext
```

### How to use
```go
package main

import (
	"fmt"
	"github.com/shamsher31/goarchext"
)

func main() {
	fmt.Println(archext.Get())
}
```

### Why
This package is inspired by [archive-extensions](https://www.npmjs.com/package/archive-extensions) npm module.

# License
MIT © [Shamsher Ansari](https://github.com/shamsher31)
