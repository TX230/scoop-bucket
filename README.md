# TX230 Scoop Bucket

[![Tests](https://github.com/TX230/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/TX230/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/TX230/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/TX230/scoop-bucket/actions/workflows/excavator.yml)

Scoop manifests for applications maintained by [TX230](https://github.com/TX230).

## Install

Add this bucket:

```powershell
scoop bucket add tx230 https://github.com/TX230/scoop-bucket
```

Install `winproc-tui`:

```powershell
scoop install tx230/winproc-tui
```

## Update

Update Scoop and its buckets, then update `winproc-tui`:

```powershell
scoop update
scoop update winproc-tui
```

## Uninstall

Normal uninstall keeps the persisted `winproc-tui.toml` configuration:

```powershell
scoop uninstall winproc-tui
```

Use `--purge` to remove the persisted configuration as well:

```powershell
scoop uninstall --purge winproc-tui
```

## Applications

| Manifest | Description | Homepage |
|---|---|---|
| `winproc-tui` | Windows process investigation TUI | [TX230/winproc-tui](https://github.com/TX230/winproc-tui) |

## License

The bucket infrastructure is based on
[ScoopInstaller/BucketTemplate](https://github.com/ScoopInstaller/BucketTemplate).
Each application is distributed under the license declared in its manifest.
