# go-mastodon

Pure-Go read client for the Mastodon REST API.

go-mastodon is a pure-Go, dependency-free read client for the Mastodon REST API. It reads public, hashtag and per-account timelines with Link-header pagination. CGO_ENABLED=0 (no C, static binaries everywhere), standard library only, 100% test coverage via network-free tests.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Packages

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/mastodon.md"><code>mastodon</code><br><small>Pure-Go read client for the Mastodon REST API. CGO=0, zero third-party deps.</small></a>
</div>
