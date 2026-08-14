# tenequm's Scoop bucket

[![Tests](https://github.com/tenequm/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/tenequm/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/tenequm/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/tenequm/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for [pond](https://github.com/tenequm/pond) - lossless storage and search for sessions from any AI agent client.

## Install

```pwsh
scoop bucket add tenequm https://github.com/tenequm/scoop-bucket
scoop install pond
```

## Manifests

| App | Description |
|---|---|
| [pond](https://pond.locker/) | Lossless storage and search for sessions from any AI agent client |

Manifests track the `x86_64-pc-windows-msvc` zip attached to each [pond release](https://github.com/tenequm/pond/releases). Excavator updates them automatically every four hours; the hash comes from the release asset's own digest.

pond is also on winget (`winget install tenequm.pond`).
