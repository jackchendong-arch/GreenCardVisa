# GreenCardVisa
Desktop App Processing Chinese Green Card Visa Applications.

## Windows CI packaging

Every push triggers the GitHub Actions workflow in `.github/workflows/build-windows.yml`.
It installs dependencies on `windows-latest`, builds a Windows NSIS installer with `electron-builder`,
and uploads the packaged output as a workflow artifact from the Actions run summary.
