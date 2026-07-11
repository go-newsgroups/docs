# newznab

A pure-Go, dependency-free client for the Newznab Usenet indexer API. It works against direct Newznab indexers (nzbgeek, NZBFinder, DrunkenSlug, …) and against NZBHydra2, which exposes a Newznab-superset API. Implements the `t=search` and `t=caps` endpoints; the base URL is overridable for fully network-free testing. `CGO_ENABLED=0`, standard library only.

## Install

```bash
go get github.com/go-newsgroups/newznab
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-newsgroups/newznab>
- API reference: <https://pkg.go.dev/github.com/go-newsgroups/newznab>

!!! note
    See the module's README for full, up-to-date details.
