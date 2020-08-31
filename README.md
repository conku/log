# Logger

A logger middleware for Gin

[![GoDoc](https://godoc.org/github.com/conku/log?status.svg)](https://godoc.org/github.com/conku/log)

## Usage

```go
import "github.com/conku/log"

func main() {
  router := gin.New()
  router.Use(log.Logger("application.log", 30)) // save logs into application.log, max days is 30
}
```

## License

Released under the [MIT License](http://opensource.org/licenses/MIT).
