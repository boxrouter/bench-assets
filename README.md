# bench-assets

Digest-pinned workload files and static tools that the [Sandbox Provider Benchmarks](https://github.com/boxrouter/sandbox-provider-benchmarks) download into sandboxes during benchmark runs.

This repository holds static Linux benchmark executables (7-Zip, STREAM, fio, and stress-ng), a small Vite web application, and R2E-Gym software engineering task tarballs. It is used by the benchmark runner and by developers or providers who reproduce benchmark runs against services that implement the [Sandbox Provider Spec](https://github.com/boxrouter/sandbox-provider-spec) (SPS).

Assets are published only as releases of this repository so that every run downloads the exact same bytes. Every download is verified against a SHA-256 digest that is pinned in the benchmark definition that uses it. See [NOTICES.md](NOTICES.md) for the upstream source and license of each file.
