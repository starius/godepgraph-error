The repo was created to demonstrate error in godepgraph, failure to locate some vendored packages.

```
$ godepgraph github.com/starius/godepgraph-error
2018/05/24 22:37:19 failed to import bar.com/bar: cannot find package "bar.com/bar" in any of:
        /GOROOT/src/bar.com/bar (from $GOROOT)
        /GOPATH/src/bar.com/bar (from $GOPATH)
```
