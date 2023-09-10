# create-a-go-module

Learning how to use Go module (https://go.dev/doc/tutorial/create-module)

## Command:

- `go run .`
- `go mod init example.com/xxx`
- `go mod edit -replace example.com/xxx=../xxx` -> Change the module import's location
- `go mod tidy`
- `go test`
- `go test -v`
- `go build` -> compiles the packages with their dependencies, but it doesn't install the results
- `go install` -> compiles and installs the packages
- `go list -f '{{.Target}}'` -> discovery the install path
- `go env -w GOBIN=/path/to/your/bin` -> Change install target
