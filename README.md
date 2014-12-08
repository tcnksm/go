Go
====

This is the source code repository for the Go programming language.  

For documentation about how to install and use Go,
visit [http://golang.org/](http://golang.org/) or load `doc/install-source.html` in your web browser.

After installing Go, you can view a nicely formatted
`doc/install-source.html` by running `godoc --http=:6060`
and then visiting [http://localhost:6060/doc/install/source](http://localhost:6060/doc/install/source).

Unless otherwise noted, the Go source files are distributed
under the BSD-style license found in the [LICENSE](https://github.com/golang/go/blob/master/LICENSE) file.

## Binary Distribution Notes

If you have just untarred a binary Go distribution, you need to set the environment variable `$GOROOT` to the full path of the go
directory (the one containing this README).  You can omit the
variable if you unpack it into `/usr/local/go`, or if you rebuild
from sources by running all.bash (see `doc/install.html`).
You should also add the Go binary directory `$GOROOT/bin`
to your shell's path.

For example, if you extracted the tar file into `$HOME/go`, you might
put the following in your `.profile`:

```bash
export GOROOT=$HOME/go
export PATH=$PATH:$GOROOT/bin
```

See `doc/install.html` for more details.
