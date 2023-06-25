# Go

- website: https://go.dev/
- playground: https://go.dev/play/
- release history: https://go.dev/doc/devel/release
- frequently asked questions: https://go.dev/doc/faq
- go doc comments: https://go.dev/doc/comment
- godoc tool: https://go.dev/blog/godoc
- go command: https://pkg.go.dev/cmd/go
- GitHub: https://github.com/golang/go
- Twitter: https://twitter.com/golang

## Release Notes:

- Go 1.20: https://go.dev/doc/go1.20
- Go 1.19: https://go.dev/doc/go1.19
- Go 1.18: https://go.dev/doc/go1.18
- Go 1.17: https://go.dev/doc/go1.17

## Style Guides

- [Effective Go](https://go.dev/doc/effective_go)
- [Uber Go Style Guide](https://github.com/uber-go/guide)
- [Google Go Style Guide](https://google.github.io/styleguide/go/)

## Language Specification

- https://go.dev/ref/spec

Notes:

- Switch statements: expression switches and type switches.
- A "select" statement chooses which of a set of possible send or receive operations will proceed.
- A "break" statement terminates execution of the innermost "for", "switch", or "select" statement within the same function.
- The length of a nil slice, map or channel is 0. The capacity of a nil slice or channel is 0.
- Receiving from a nil channel blocks forever.

## -
- Memory Model: https://go.dev/ref/mem
- A Guide to the Go Garbage Collector: https://go.dev/doc/gc-guide
- Deprecation of 'go get' for installing executables: https://go.dev/doc/go-get-install-deprecation
- Getting to Go: The Journey of Go's Garbage Collector: https://go.dev/blog/ismmkeynote

```shell
go install golang.org/x/tools/cmd/godoc@latest
```

```mermaid
timeline
    title History
    2012-03-08 : go1
    2013-05-13 : go1.1
    2013-12-01 : go1.2
    2022-03-15 : go1.18
    2022-08-02 : go1.19
    2023-02-01 : go1.20
```
