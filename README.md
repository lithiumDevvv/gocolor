# Go color is a simple golang package for adding color to terminal output.
```
This package includes:
- Normal colors
- Bold colors 
- Underlined colors
- High Intensity Colors 
- Bold High Intensity Colors
```

# Commands
```
command -> go get github.com/lithiumDevvv/gocolor/
```

# Usage
```golang
package main

import (
  "fmt"
  "github.com/lithiumDevvv/gocolor"
)

func main() {
  fmt.Println(gocolor.RedBold("Some Bold Red Text") + gocolor.Blank())
}
```
![image](https://user-images.githubusercontent.com/115331024/194685117-76217399-0e38-41cf-be83-31a6da9098fc.png)
