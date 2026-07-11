# yenc

Pure-Go, dependency-free **yEnc** and **uuencode** decoders and encoders for Usenet binary posts. A yEnc article body runs from `=ybegin` to `=yend`; `Decode` returns the part with its name, size and CRC32 (surfacing `ErrCRCMismatch` on a corrupt post), and `Encode` produces one. `CGO_ENABLED=0`, 100% statement coverage on every supported architecture.

## Install

```bash
go get github.com/go-newsgroups/yenc
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-newsgroups/yenc>
- API reference: <https://pkg.go.dev/github.com/go-newsgroups/yenc>

!!! note
    See the module's README for full, up-to-date details.
