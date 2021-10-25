# Duktape stub

[duktape](https://gopkg.in/olebedev/go-duktape.v3) requires `CGO_ENABLED=1`.

This stub exists as a drop-in replacement for the original implementation - so you can continue to build/use your projects without `CGO_ENABLED=1`.

## How to use

Use the following replace directive in your projects `go.mod`:

```go.mod
// go.mod

require(
  ...
)

replace gopkg.in/olebedev/go-duktape.v3 => github.com/zees-dev/duktape-stub@latest
```

## Original source

[https://gitlab.com/vocdoni/go-dvote/-/tree/v0.6.2/duktape-stub](https://gitlab.com/vocdoni/go-dvote/-/tree/v0.6.2/duktape-stub)
