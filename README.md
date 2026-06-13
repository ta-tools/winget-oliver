# winget-oliver — winget manifests for Oliver (Windows)

winget manifests for **Oliver (AskWashU APIM Explorer)** —
`PackageIdentifier: WashU.Oliver`. Regenerated each release by
`release-to-pkgs.sh`; the installer is the Azure Trusted-Signed `.exe` mirrored
at `ta-tools/oliver-release`.

## Install

These are private manifests (not in the public winget community source), so
install them directly from a clone:

```powershell
git clone https://github.com/ta-tools/winget-oliver
winget install --manifest winget-oliver\manifests\w\WashU\Oliver\<version>
```

Or skip winget and run the signed installer straight from the mirror:
<https://github.com/ta-tools/oliver-release/releases/latest>

## Update

Re-run `winget install --manifest` against the newer version folder, or
`winget upgrade WashU.Oliver` once a matching manifest is installed.
