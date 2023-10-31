# Azure Data Studio Network Proxy Test
Azure Data Studio's Network proxy test extension, extended from https://github.com/chrmarti/vscode-network-proxy-test

## Commands
Below commands are supported:
- `Proxy Test: Test Network Connection (HTTP)`
- `Proxy Test: Test Network Connection (HTTP2)`
- `Proxy Test: Test Network Connection (Fetch)`
- `Proxy Test: Test Network Connection (Axios)`
- `Proxy Test: Show OS Certificates (VS Code)`
- `Proxy Test: Show Built-In Certificates (VS Code)`

## Usage:
1. Download extension in `extensions\` directory.
2. Run ADS in debug session.
3. Run command `F1` > `Proxy Test: Test Network Connection (<any>)`, enter the URL to test or use default. This will open a new editor and log the results.
If that shows a certificate error, read further down in the editor to get information on the certificate chain in the server's response.
4. Use `F1` > `Proxy Test: Show <any> Certificates` to check if the required root certificate is loaded from the OS/build-in cert store.

## License
[MIT](LICENSE)
