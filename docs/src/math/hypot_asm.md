# hypot_asm.go

```go
// Copyright 2021 The Go Authors. All rights reserved.
// Use of this source code is governed by a BSD-style
// license that can be found in the LICENSE file.

//go:build 386 || amd64

package math

const haveArchHypot = true

func archHypot(p, q float64) float64
```
