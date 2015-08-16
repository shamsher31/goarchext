# goarchext
List of Archive file extensions for Go

# How to install
<pre>
go get github.com/shamsher31/goarchext
</pre>

# How to use
<pre>
package main

import (
	"fmt"
	"github.com/shamsher31/goarchext"
)

func main() {
	fmt.Println(archext.Get())
}
</pre>

# Why
This package is inspired by [archive-extensions](https://www.npmjs.com/package/archive-extensions) npm module for Archive extension.

# License
MIT © [Shamsher Ansari](https://github.com/shamsher31)
