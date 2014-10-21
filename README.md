Goappp
===

Goappp is a GOPATH resolution tool along the lines of vegasje/gop. It allows you to execute Goapp commands with local GOPATH resolution.

For example, if your directory structure looks like this:

```sh
project
	src
		github.com
			username
				project
					subpackage
						subpackage.go
					main.go
```

The following command would set GOPATH to project anywhere inside of project/github.com/username/project:
- goappp serve
