# par2

Pure-Go (CGO-free) parser, verifier and repairer for **PAR2** recovery sets — the format behind the AutoPAR feature that protects Usenet binaries. Parse concatenated `.par2` blobs into a `RecoverySet` (validating each packet's MD5), verify files with the per-slice MD5+CRC32 checksums, and repair damaged slices via Reed-Solomon over GF(2^16). The Galois-field core is reused from `go-erasure/reedsolomon`.

## Install

```bash
go get github.com/go-newsgroups/par2
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-newsgroups/par2>
- API reference: <https://pkg.go.dev/github.com/go-newsgroups/par2>

!!! note
    See the module's README for full, up-to-date details.
