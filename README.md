# duckvhuynh's Scoop bucket

[![Tests](https://github.com/duckvhuynh/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/duckvhuynh/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/duckvhuynh/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/duckvhuynh/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for [QuickCopy](https://github.com/duckvhuynh/quickcopy):
select, copy and translate the text in any on-screen image or paused video.

## Install

```pwsh
scoop bucket add duckvhuynh https://github.com/duckvhuynh/scoop-bucket
scoop install duckvhuynh/quickcopy
```

Start QuickCopy from the Start menu shortcut or with `quickcopy`. Update it with
`scoop update quickcopy`.

## Manifests

| App | Manifest |
| --- | --- |
| QuickCopy | [bucket/quickcopy.json](bucket/quickcopy.json) |

The Excavator workflow checks for new QuickCopy releases every 4 hours and updates
the version and hash from the release's `SHA256SUMS.txt`.
