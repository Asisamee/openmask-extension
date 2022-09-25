# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.7.0] - 2022-09-25

### Uncategorized

- Add `ton_rawSing` method and notification view
- Add `ton_personalSing` method and notification view
- Add `wallet_watchAsset` method and notification view
- Add Jetton list on home page
- Add Jetton page with send feature and import by minter contract address features

## [0.6.1] - 2022-09-17

### Changed

- QR code on Receive page
- Update libs version
- Optimise build, remove unnecessary dependencies

## [0.6.0] - 2022-09-10

### Changed

- Update wallet permissions. Added Locked permission, to allow dApps read base information from locked wallet
- Fixing layout issue and formalizing ton value issue
- Make narrowest extension permissions

## [0.5.0] - 2022-09-07

### Uncategorized

- A key vault for multiple wallets
- Switch TON mainnet/testnet in one click
- Sending zero-commission transactions (only network fee) from the application
- Support TON DNS
- Inpage TON provider
  - Read addresses and balances, suggest transactions
  - Manage network
- DApps whitelist with permissions
- Fiat balance, activity list
- Wallets settings to manage version and bounceable address type

[unreleased]: https://github.com/OpenProduct/openmask-extension/compare/v0.7.0...HEAD
[0.7.0]: https://github.com/OpenProduct/openmask-extension/compare/v0.6.1...v0.7.0
[0.6.1]: https://github.com/OpenProduct/openmask-extension/compare/v0.6.0...v0.6.1
[0.6.0]: https://github.com/OpenProduct/openmask-extension/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/OpenProduct/openmask-extension/releases/tag/v0.5.0