# Panic and Recover

Spec: https://go.dev/ref/spec#Handling_panics

```go
func panic(interface{})
func recover() interface{}
```

## Examples

```go
func main() {
	panic(nil)
}

/*
panic: panic called with nil argument
*/
```

```go
func main() {
	var m map[string]string
	m["key"] = "value"
}

/*
panic: assignment to entry in nil map
*/
```

```go
func main() {
	_ = 2 / func() int { return 0 }()
}

/*
panic: runtime error: integer divide by zero
*/
```

```go
func main() {
	defer panic("c")
	defer panic("b")
	panic("a")
}

/*
panic: a
	panic: b
	panic: c
*/
```
