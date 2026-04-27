# cdn.getpaidinbitcoin.com.au

Public asset repository for [Get Paid In Bitcoin](https://getpaidinbitcoin.com.au).

Hosts hero images, partner logos, and other static assets used by the GPIB portal and public landing pages. Kept public so they can be served via [jsDelivr](https://www.jsdelivr.com/).

## Usage

Images are served at:

```
https://cdn.jsdelivr.net/gh/GetPaidInBitcoin/cdn.getpaidinbitcoin.com.au@main/images/<filename>
```

Example:

```
https://cdn.jsdelivr.net/gh/GetPaidInBitcoin/cdn.getpaidinbitcoin.com.au@main/images/hero-getting-started.jpg
```

## Layout

- `images/` — hero images, partner logos, and other site graphics.

## Adding new assets

1. Add the file under `images/`.
2. Commit and push to `main`.
3. The new asset is available via the jsDelivr URL above (jsDelivr caches aggressively — append `@<commit-sha>` instead of `@main` to bypass).
