# go-adodb

Microsoft ADODB driver conforming to the built-in database/sql interface

## Installation

This package can be installed with the go get command:

    go get github.com/2432001677/go-adodb

## Documentation

Examples can be found under the `./_example` directory

## Note

If you met the issue that your apps crash, try to import blank import of `runtime/cgo` like below.

```go
import (
    ...
    _ "runtime/cgo"
)
```

## License

MIT: http://mattn.mit-license.org/2015

## Author

Yasuhiro Matsumoto (a.k.a mattn)
