## Hi, I'm ctxloop

Go backend engineer & AI builder.

### Open source

- **[oras-project/oras-go](https://github.com/oras-project/oras-go)** — perf: avoid allocating 3x the content size in `ReadAll` ([#1426](https://github.com/oras-project/oras-go/pull/1426)); fix: bound how far a registry can raise the chunk size in chunked blob push ([#1464](https://github.com/oras-project/oras-go/pull/1464)); fix: stop the OCI store from leaking a manifest after its tag moves ([#1469](https://github.com/oras-project/oras-go/pull/1469)); perf: send the Range request on `Read` instead of on every `Seek` ([#1473](https://github.com/oras-project/oras-go/pull/1473)); perf: stop the OCI store's `Delete` from copying the whole tag index for every node it removes ([#1483](https://github.com/oras-project/oras-go/pull/1483))
