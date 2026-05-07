# EasyBlocks Pro — Release Manifest

This repo hosts the public **`latest.json`** manifest used by the EasyBlocks Pro After Effects panel to detect new versions and prompt users to update.

The actual `.zxp` and `.zip` artifacts are stored on NVIDIA SharePoint (auth-required); only the version metadata is here.

## File format
```json
{
  "version": "1.3.2",
  "zxp": "EasyBlocksPro-1.3.2.zxp",
  "update": "EasyBlocksPro-1.3.2-update.zip",
  "releasedAt": "2026-05-07T12:00:00Z",
  "notes": "Optional release notes"
}
```

Updated automatically by `build.sh` in the EasyBlocks Pro plugin source on every release.
