# wget

GNU Wget 1.24.5 with HTTPS (the ca-certificates package)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install wget
```

| | |
|---|---|
| Version | 1.24.5 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`openssl`](https://github.com/Artfical/tpkg-openssl), [`zlib`](https://github.com/Artfical/tpkg-zlib), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 619 or newer |
| Size | 230726 bytes (470554 unpacked) |
| SHA-256 of the `.tpkg` | `6e61c352a3ec0e518fac0d9edc81be1222ebafda01d3924662acce7c1784eaa0` |

## Commands it adds

| Command | Runs |
|---|---|
| `wget` | `bin/wget` |

## Download

The package file (`wget-1.24.5.tpkg`) and the sources it was built from are the assets of the
[v1.24.5 release](https://github.com/Artfical/tpkg-wget/releases/tag/v1.24.5).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `wget-1.24.5.tar.gz`

Check a download: `sha256sum wget-1.24.5.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
