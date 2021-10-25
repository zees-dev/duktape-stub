# Duktape stub

[Duktape](https://github.com/olebedev/go-duktape) is a thin, embeddable javascript engine.

The original implementation of [duktape](https://gopkg.in/olebedev/go-duktape.v3) requires `CGO_ENABLED=1`.

This stub exists as a drop-in replacement for the original implementation - so you can continue to build/use your projects without `CGO_ENABLED=1`.

## How to use

```sh
go get github.com/zees-dev/duktape-stub@v1.0.0
```

Use the following replace directive in your projects `go.mod`:

```go.mod
// go.mod

require(
  ...
)

replace gopkg.in/olebedev/go-duktape.v3 => github.com/zees-dev/duktape-stub v1.0.0
```

## Original source

[https://gitlab.com/vocdoni/go-dvote/-/tree/v0.6.2/duktape-stub](https://gitlab.com/vocdoni/go-dvote/-/tree/v0.6.2/duktape-stub)

Use-case: [https://github.com/ethereum/go-ethereum/issues/20590#issuecomment-613434500](https://github.com/ethereum/go-ethereum/issues/20590#issuecomment-613434500).
