# mastodon

A pure-Go, dependency-free **read** client for the Mastodon REST API. Reads public, hashtag and per-account timelines and follows the `Link` header for pagination. Construct a client with `mastodon.New` against any instance, optionally with a user agent and bearer token. `CGO_ENABLED=0`, standard library only, 100% test coverage via `net/http/httptest`.

## Install

```bash
go get github.com/go-mastodon/mastodon
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-mastodon/mastodon>
- API reference: <https://pkg.go.dev/github.com/go-mastodon/mastodon>

!!! note
    See the module's README for full, up-to-date details.
