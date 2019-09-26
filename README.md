# semver
POC of go modules and semantic versioning:

https://github.com/golang/go/wiki/Modules#semantic-import-versioning

```go
package main

import (
	"fmt"
	"github.com/arpando/semver"
	semverV2 "github.com/arpando/semver/v2"
)

func main() {
	fmt.Println(semver.SayHello())
	fmt.Println(semverV2.SayHello("Arkan"))
}
```
