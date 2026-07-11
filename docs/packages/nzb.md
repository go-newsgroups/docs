# nzb

A pure-Go library to **parse NZB files** and **download and reassemble** their binary content over NNTP, decoding yEnc article bodies. `Parse` reads the newzbin NZB DTD (tolerating the non-UTF-8 charset declarations real files carry); `DownloadFile` fetches each segment through any `ArticleFetcher` (satisfied by `*nntp.Conn`), yEnc-decodes it, and tiles multipart parts by their yEnc `begin` offset. Depends only on the sibling `nntp` and `yenc` modules.

## Install

```bash
go get github.com/go-newsgroups/nzb
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-newsgroups/nzb>
- API reference: <https://pkg.go.dev/github.com/go-newsgroups/nzb>

!!! note
    See the module's README for full, up-to-date details.
