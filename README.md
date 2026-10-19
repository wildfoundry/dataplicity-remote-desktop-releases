# Dataplicity Remote Desktop

Windows and Linux install packages for Dataplicity Remote Desktop. Development
stays in a private repository; this repository publishes **release artifacts
only**.

## About

Dataplicity Remote Desktop is a remote-admin client for Dataplicity OEM and
developer workflows. Install the package for your OS, then enrol the host with
your organisation from the Dataplicity dashboard.

macOS installs are distributed via the [Homebrew tap](https://github.com/wildfoundry/homebrew-tap)
(`brew install wildfoundry/tap/dataplicity-remote-desktop`).

For more information, see https://docs.dataplicity.com and
https://www.dataplicity.com/.

## Packages

See [Releases](https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases)
for downloadable files.

| Asset | Use |
| --- | --- |
| `dataplicity-remote-desktop-<version>-windows-x64.msi` | Windows installer (signed when release signing is configured) |
| `dataplicity-remote-desktop_<version>_<arch>.deb` | Debian / Ubuntu (`amd64`, `arm64`) |
| `dataplicity-remote-desktop-<version>-1.<arch>.rpm` | RPM (`x86_64`, `aarch64`) |
| `dataplicity-remote-desktop-<version>-linux-<arch>.tar.gz` | Standalone Linux binary tarball |
| `SHA256SUMS-*.txt` | Per-platform SHA-256 checksums |

Verify downloads before installing:

```sh
# Linux example
sha256sum --check SHA256SUMS-linux-x86_64.txt
```

## License

Dataplicity Remote Desktop is licensed under a modified-BSD license. See
[LICENSE.txt](LICENSE.txt).
