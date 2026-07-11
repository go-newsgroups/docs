# nntp

A dependency-free, pure-Go **NNTP (Usenet) read client** following RFC 3977, using only the standard library (`net`, `net/textproto`, `crypto/tls`). Supported operations: connect (plaintext or implicit TLS), `AUTHINFO` authentication, `GROUP` selection, `OVER` overview retrieval, `ARTICLE` fetching, and `LIST ACTIVE` newsgroup enumeration. `CGO_ENABLED=0`, zero third-party dependencies.

## Install

```bash
go get github.com/go-newsgroups/nntp
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-newsgroups/nntp>
- API reference: <https://pkg.go.dev/github.com/go-newsgroups/nntp>

!!! note
    See the module's README for full, up-to-date details.
