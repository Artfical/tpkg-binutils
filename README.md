# binutils

GNU binutils 2.46.1: as, ld, ar, nm, objdump, objcopy, readelf, strip (64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install binutils
```

| | |
|---|---|
| Version | 2.46.1 |
| Licence | GPL-3.0+ |
| Upstream | https://www.gnu.org/software/binutils/ |
| Needs | [`glibc-dev`](https://github.com/Artfical/tpkg-glibc-dev) |
| Needs tOS build | 615 or newer |
| Size | 9409618 bytes (23331408 unpacked) |
| SHA-256 of the `.tpkg` | `bd6c86a0132cafd17451ad7cdc0aa662f445db2b7eb3caa8fb2b68ba7fc4bc3a` |

## Commands it adds

| Command | Runs |
|---|---|
| `as` | `bin/as` |
| `ld` | `bin/ld` |
| `ar` | `bin/ar` |
| `ranlib` | `bin/ranlib` |
| `nm` | `bin/nm` |
| `objdump` | `bin/objdump` |
| `objcopy` | `bin/objcopy` |
| `readelf` | `bin/readelf` |
| `strip` | `bin/strip` |
| `size` | `bin/size` |
| `strings` | `bin/strings` |
| `addr2line` | `bin/addr2line` |
| `c++filt` | `bin/c++filt` |
| `elfedit` | `bin/elfedit` |
| `gprof` | `bin/gprof` |

## Download

The package file (`binutils-2.46.1.tpkg`) and the sources it was built from are the assets of the
[v2.46.1 release](https://github.com/Artfical/tpkg-binutils/releases/tag/v2.46.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `binutils-2.46.1.tar.xz`

Check a download: `sha256sum binutils-2.46.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0+. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
