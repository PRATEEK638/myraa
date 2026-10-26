![MYRAA](docs/assets/banner.svg)

# Myraa

Windows desktop companion application.

**Focus:** Desktop assistant / project archive  
**Stack:** Windows · Electron · TypeScript · Python agent (original source unavailable)

[LinkedIn](https://www.linkedin.com/in/prateek-sharma-97a064296/) · [Portfolio projects](docs/PORTFOLIO.md)

## Project overview

This repository preserves the MYRAA 1.0.1 Windows installer and a partial source recovery from the installed application. The installer remains available in [Releases](https://github.com/PRATEEK638/myraa/releases/tag/local-import-2026-10-10).

## Source recovery

The `source_recovery/` directory contains TypeScript, Electron, and API hub files extracted from the installed distribution's source maps. This is a partial recovery snapshot, not the original complete development project.

The original React/TypeScript frontend source and Python desktop-agent source were not present in the recovered source map. Build output, dependencies, and runtime media/model assets are omitted. The supplied files do not include enough project metadata to establish a reproducible build, and no build or runtime test is claimed for this snapshot.

No license file was present in the recovered project. This repository does not assert an open-source license for the recovered files; rights and third-party attribution should be confirmed before redistribution or reuse.

## Interface preview

![MYRAA desktop interface](docs/assets/myraa-interface.png)

This screenshot shows a captured prototype session, rather than a new performance or runtime test.

## Repository map

| Path | Contents |
|---|---|
| `source_recovery/` | Partial source-map recovery, installed dependency metadata, and recovery manifest |
| `docs/` | Existing portfolio notes and screenshots |
| GitHub Releases | MYRAA 1.0.1 Windows installer and checksum |

## Downloads

[Open project releases](https://github.com/PRATEEK638/myraa/releases/tag/local-import-2026-10-10)

| File | Size | SHA-256 |
|---|---:|---|
| `MYRAA-Setup-1.0.1.exe` | 148.7 MiB | `e4a4fd9c8a3190444ea9e57a8fc9f18ef5531b52ca6a4417fc1e1fbb9d306fb0` |

## Project status

The installer is preserved and partial source files are now included for review. This source recovery has not been rebuilt or runtime-tested.