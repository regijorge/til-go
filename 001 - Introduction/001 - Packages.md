# Packages

Every go program is made up of packages

Programs start running in packages main

By convention the package name is the same as the last element of the import path. For instance, the "math/rand" package comprizes files that begin with the statement package "rand"

```go
package main

import (
	"fmt"
	"math/rand"
)

func main() {
	fmt.Println("My favorite number is", rand.Intn(10))
}

// => 
// My favorite number is 6
```
