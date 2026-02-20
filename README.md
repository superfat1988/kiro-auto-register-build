# Kiro Auto Register - GitHub Actions Build

This repository provides automated builds for [Pluviobyte/Kiro-auto-register](https://github.com/Pluviobyte/Kiro-auto-register) using GitHub Actions.

## ⚠️ Risk Warning

This tool is for **educational purposes only**. Automated registration of AWS/Kiro accounts may:
- Violate AWS Terms of Service
- Result in account suspension
- Involve credential security risks

Use at your own risk.

## Build Status

| Platform | Status |
|----------|--------|
| Windows | ![Build Windows](https://github.com/superfat1988/kiro-auto-register-build/actions/workflows/build-electron.yml/badge.svg?branch=main&job=build-windows) |
| macOS | ![Build macOS](https://github.com/superfat1988/kiro-auto-register-build/actions/workflows/build-electron.yml/badge.svg?branch=main&job=build-macos) |
| Linux | ![Build Linux](https://github.com/superfat1988/kiro-auto-register-build/actions/workflows/build-electron.yml/badge.svg?branch=main&job=build-linux) |

## Download Builds

1. Go to [Actions](../../actions) tab
2. Select the latest successful workflow run
3. Download artifacts for your platform:
   - Windows: `.exe` or `.msi`
   - macOS: `.dmg`
   - Linux: `.AppImage` or `.deb`

## Manual Build Trigger

To manually trigger a build:
1. Go to [Actions](../../actions) tab
2. Select "Build Kiro Auto Register"
3. Click "Run workflow"

## Original Repository

- Source: https://github.com/Pluviobyte/Kiro-auto-register
- Description: Kiro自动注册，支持邮件验证码获取和多平台账号管理
