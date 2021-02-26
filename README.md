# ptr [![GoDoc](https://godoc.org/github.com/akabos/ptr?status.svg)](https://godoc.org/github.com/akabos/ptr) [![Go Report Card](https://goreportcard.com/badge/github.com/akabos/ptr)](https://goreportcard.com/report/github.com/akabos/ptr)

`ptr` contains functions for simplified creation of pointers from constants of basic types.

## Installation

`go get github.com/akabos/ptr`

## Examples

This code:

```go
p := ptr.Int(10)
```

is the equivalent for:

```go
i := int(10)
p := &i  
```

## Documentation

[GoDoc](http://godoc.org/github.com/gotidy/ptr)

## License

[Apache 2.0](https://github.com/gotidy/ptr/blob/master/LICENSE)
