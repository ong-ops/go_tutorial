# multi-module-workspace

Learning how to create multi-module workspaces (https://go.dev/doc/tutorial/workspaces)

## Command:

- `go get golang.org/x/example/hello/reverse` -> add a dependency
- `go work init ./hello` -> create a workspace for hello dir
- `go work use [-r] ./example/hello` -> add the module to the workspace (-r is dir recursive)
- `go work edit` -> edits the go.work file
- `go work sync` -> sync dependencies from the workspace's build list into each of the workspace modules
