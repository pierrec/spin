# spin

A very simple spinner for cli golang apps.

[![Release](https://img.shields.io/github/release/caarlos0/spin.svg?style=flat-square)](https://github.com/caarlos0/spin/releases/latest)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Travis](https://img.shields.io/travis/caarlos0/spin.svg?style=flat-square)](https://travis-ci.org/caarlos0/spin)
[![Coverage Status](https://img.shields.io/coveralls/caarlos0/spin/master.svg?style=flat-square)](https://coveralls.io/github/caarlos0/spin?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/caarlos0/spin?style=flat-square)](https://goreportcard.com/report/github.com/caarlos0/spin)
[![](https://godoc.org/github.com/caarlos0/spin?status.svg&style=flat-square)](http://godoc.org/github.com/caarlos0/spin)
[![SayThanks.io](https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg?style=flat-square)](https://saythanks.io/to/caarlos0)

Example usage:

```go
package main

import (
	"fmt"
	"time"

	"github.com/caarlos0/spin"
)

func main() {
	s := spin.New("%s Working...")
	s.Start()
  defer s.Stop()
	time.Sleep(100 * 20 * time.Millisecond)
}
```

[![asciicast](https://asciinema.org/a/97581.png)](https://asciinema.org/a/97581)
