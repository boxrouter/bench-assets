# Notices

Each release asset is unmodified third-party material (or a build of it from the source published beside it),
distributed under its own licence. Licence texts are in `LICENSES/`. The `SHA256SUMS` asset of each release
lists every file in it; `tools-v1.SHA256SUMS` and `r2e-gym-v1.SHA256SUMS` in the repository are the same lists.

## Release `tools-v1`

| Asset | Source | Licence |
| --- | --- | --- |
| `7zzs-25.01-linux-x64-static` | `7zzs` from Igor Pavlov's `7z2501-linux-x64.tar.xz` (also an asset), https://www.7-zip.org/ | GNU LGPL with the unRAR restriction, BSD 3-clause for some code (`LICENSES/7-Zip-LGPL-unRAR.txt`) |
| `stream-5.10-80m-linux-x86_64-static` | STREAM 5.10 by John McCalpin, `stream.c` (an asset), https://www.cs.virginia.edu/stream/ | STREAM licence (`LICENSES/STREAM.txt`) |
| `fio-3.39-linux-x86_64-static` | fio 3.39, https://github.com/axboe/fio, built from `fio-3.39.tar.gz` and `libaio_0.3.113.orig.tar.gz` (both assets) | GPL-2.0 (fio, `LICENSES/GPL-2.0.txt`); libaio is LGPL-2.1 (`LICENSES/LGPL-2.1.txt`) |
| `stress-ng-0.19.02-linux-x86_64-static.xz` | stress-ng V0.19.02, https://github.com/ColinIanKing/stress-ng, built from `stress-ng-0.19.02.tar.gz` (an asset) | GPL-2.0-or-later (`LICENSES/GPL-2.0.txt`) |
| `previews-app-vite-8.3.4.tar.xz` | A minimal app and its npm dependencies installed with Vite 8.3.4, https://vite.dev/ | MIT for Vite (`LICENSES/vite-MIT.md`); each bundled package carries its own licence file inside the archive |
| `BUILD-cpu-tools.md`, `BUILD-disk-tools.md` | Build notes for the binaries above | - |

The corresponding source for the GPL and LGPL binaries (`fio-3.39.tar.gz`, `libaio_0.3.113.orig.tar.gz`,
`stress-ng-0.19.02.tar.gz`) is in the same release, with the exact build commands in `BUILD-disk-tools.md`.

## Release `r2e-gym-v1`

Task checkouts from the R2E-Gym dataset: each tarball holds one repository at a fixed commit with its Python
environment (`testbed/`). The repository history and the installed packages each keep their own licence files.

| Assets | Source | Licence |
| --- | --- | --- |
| `numpy-*.tar.gz` (four) | https://github.com/numpy/numpy | BSD 3-clause (`LICENSES/numpy-BSD-3-Clause.txt`) |
| `coveragepy-*.tar.gz` | https://github.com/nedbat/coveragepy | Apache-2.0 (`LICENSES/coveragepy-Apache-2.0.txt`, `LICENSES/coveragepy-NOTICE.txt`) |
