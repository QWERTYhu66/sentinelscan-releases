# SentinelScan — Releases

Download page and Windows auto-update feed for **SentinelScan**, an
authorized-scope vulnerability scanner for macOS and Windows.

This repository contains only compiled release artifacts, so no source code.
Grab the latest build from the [**Releases**](../../releases) tab.

## Downloads

| Platform | File | Notes |
|---|---|---|
| Windows (installer) | `SentinelScan-Setup-<version>.exe` | Installs + auto-updates on future releases |
| Windows (portable) | `SentinelScan-<version>.exe` | Single double-click .exe, no install (no auto-update) |
| macOS (universal) | `SentinelScan-<version>-universal.dmg` | Apple Silicon + Intel; update by re-downloading |

## First launch

The apps are unsigned, so your OS will warn once:

- **Windows:** SmartScreen → "More info" → "Run anyway".
- **macOS:** right-click the app → "Open" → "Open".

Windows installer builds check this feed on launch and update themselves;
`latest.yml` / `.blockmap` files in each release power that — please don't delete them.

## About

SentinelScan only scans targets you've added to its allowlist and attested you're
authorized to test. It has no autonomous scanning and no stealth/evasion features.
Only test systems you own or are explicitly permitted to test.
