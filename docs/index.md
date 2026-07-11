# go-newsgroups

Pure-Go Usenet: NNTP, yEnc, NZB, Newznab search, PAR2 (AutoPAR).

go-newsgroups is a family of small, composable pure-Go modules for Usenet: an RFC 3977 NNTP read client, yEnc / uuencode codecs, an NZB parser with segment download and reassembly, a Newznab / NZBHydra2 search client, and a PAR2 verify / Reed-Solomon repair library (the format behind AutoPAR). Every module is CGO_ENABLED=0 and standard-library-first.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Packages

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/newznab.md"><code>newznab</code><br><small>Client for the Newznab / NZBHydra2 indexer search API.</small></a>
<a class="pk-card" href="packages/nntp.md"><code>nntp</code><br><small>RFC 3977 NNTP (Usenet) read client — plaintext or implicit TLS.</small></a>
<a class="pk-card" href="packages/nzb.md"><code>nzb</code><br><small>NZB parser + segment download &amp; reassembly over NNTP with yEnc.</small></a>
<a class="pk-card" href="packages/par2.md"><code>par2</code><br><small>PAR2 parse / verify (MD5+CRC32) / Reed-Solomon repair (AutoPAR).</small></a>
<a class="pk-card" href="packages/yenc.md"><code>yenc</code><br><small>yEnc and uuencode decode / encode for Usenet binaries.</small></a>
</div>
