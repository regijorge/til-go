# Functions

A function can take 0 or more arguments

In this example, add takes two parameters of type ìnt``

Notice that the type comes after the variable name

```go
package main

import "fmt"

func add(x int, y int) int {
	return x + y
}

func main() {
	fmt.Println(add(42, 13))
}
```

When two or more consecutive name function parameters share a type you can omit from all but the last.

```go

func add(x, y int) int {
	return x + y
}

```
