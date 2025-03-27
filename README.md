# `try-runtime-cli` Releases
> ⚠️ NOTE: These builds are provided for development purposes only!

This repo provides cross-platform builds of `try-runtime-cli` and related binaries for usage with [`pop-cli`](https://github.com/r0gue-io/pop-cli) only.

Builds are generated using the release tags at https://github.com/paritytech/try-runtime-cli/releases.

The [workflow](./.github/workflows/release.yml) generates the cross-platform binaries and creates a corresponding release with the same release tag. The corresponding commit hash is added to the release notes for additional verification.

## Support Platforms
The currently supported platforms/targets are as follows:
- Linux
    - `aarch64-unknown-linux-gnu`
    - `x86_64-unknown-linux-gnu`
- macOS
    - `aarch64-apple-darwin`
    - `x86_64-apple-darwin`
