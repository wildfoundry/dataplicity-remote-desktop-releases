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

## Stable download links (website)

These URLs always resolve to the newest non-prerelease. Prefer them for the
Dataplicity website Add Information page and other hard-coded download buttons:

| Platform | Stable URL |
| --- | --- |
| Windows x64 MSI | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop-windows-x64.msi |
| Linux amd64 `.deb` | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop_amd64.deb |
| Linux arm64 `.deb` | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop_arm64.deb |
| Linux x86_64 `.rpm` | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop-x86_64.rpm |
| Linux aarch64 `.rpm` | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop-aarch64.rpm |
| Linux x86_64 tarball | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop-linux-x86_64.tar.gz |
| Linux aarch64 tarball | https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases/latest/download/dataplicity-remote-desktop-linux-aarch64.tar.gz |

Current version string (plain text):
https://raw.githubusercontent.com/wildfoundry/dataplicity-remote-desktop-releases/main/latest.txt

## Versioned packages

See [Releases](https://github.com/wildfoundry/dataplicity-remote-desktop-releases/releases)
for pin-able filenames that include the version.

| Asset | Use |
| --- | --- |
| `dataplicity-remote-desktop-<version>-windows-x64.msi` | Windows installer (signed when release signing is configured) |
| `dataplicity-remote-desktop_<version>_<arch>.deb` | Debian / Ubuntu (`amd64`, `arm64`) |
| `dataplicity-remote-desktop-<version>-1.<arch>.rpm` | RPM (`x86_64`, `aarch64`) |
| `dataplicity-remote-desktop-<version>-linux-<arch>.tar.gz` | Standalone Linux binary tarball |
| Stable names without `<version>` | Same bits; used by `/releases/latest/download/…` |
| `SHA256SUMS-*.txt` / `VERSION.txt` | Checksums and version stamp on each release |

Verify downloads before installing:

```sh
# Linux example (versioned asset names inside the sums file)
sha256sum --check SHA256SUMS-linux-x86_64.txt
```

## License

Dataplicity Remote Desktop is licensed under a modified-BSD license. See
[LICENSE.txt](LICENSE.txt).
