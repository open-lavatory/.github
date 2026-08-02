<p align="center">
  <a href="https://openlv.sh">
    <picture>
      <source srcset="https://raw.githubusercontent.com/v3xlabs/open-lavatory/refs/heads/master/docs/public/openlv_logo_dark.svg" media="(prefers-color-scheme: dark)">
      <img src="https://raw.githubusercontent.com/v3xlabs/open-lavatory/refs/heads/master/docs/public/openlv_logo_light.svg" alt="Open Lavatory" width="auto" height="60">
    </picture>
  </a>
</p>

<p align="center">
  Secure peer-to-peer connectivity between dApps and wallets
</p>

<p align="center">
    <a href="https://openlv.sh"><img src="https://img.shields.io/badge/Documentation-openlv.sh-orange?style=flat" alt="Documentation: openlv.sh"></a>
    <a href="#"><img src="https://img.shields.io/badge/Status-In%20Development-blue?style=flat" alt="Status: In Development"></a>
    <a href="#"><img src="https://img.shields.io/badge/Status-In%20Development-blue?style=flat" alt="Status: In Development"></a>
    <a href="#"><img src="https://img.shields.io/badge/Translations-9-blue?style=flat&color=4bdbe3" alt="Translations: 9"></a>
    <a href="#"><img src="https://img.shields.io/badge/License-LGPL--3.0-hotpink?style=flat" alt="License: LGPL-3.0"></a>
</p>

---

## Features

- Privacy-first, end-to-end encrypted, no metrics, no tracking
- No central dependency, rather a variety of [signaling layers](https://openlv.sh/api/signaling)
- Peer-to-peer transport via WebRTC (or other [transport layers](https://openlv.sh/api/transport))
- Reuse of existing infrastructure and p2p standards
- User control over connection & configuration

## Implementations

### Javascript / Typescript

| Package                                                                                                                                                             | Description                                               |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [@openlv/session](./packages/session) [![npm](https://img.shields.io/npm/v/@openlv/session.svg?color=green)](https://www.npmjs.com/package/@openlv/session)                     | a session represents a connection between dApp and wallet |
| [@openlv/signaling](./packages/signaling) [![npm](https://img.shields.io/npm/v/@openlv/signaling.svg?color=green)](https://www.npmjs.com/package/@openlv/signaling)             | Implementation of various signaling layers                |
| [@openlv/transport](./packages/transport) [![npm](https://img.shields.io/npm/v/@openlv/transport.svg?color=green)](https://www.npmjs.com/package/@openlv/transport)             | Implementation of various transport layers                |
| [@openlv/provider](./packages/provider) [![npm](https://img.shields.io/npm/v/@openlv/provider.svg?color=green)](https://www.npmjs.com/package/@openlv/provider)                 | EIP-1193 compatible provider                              |
| [@openlv/core](./packages/core) [![npm](https://img.shields.io/npm/v/@openlv/core.svg?color=green)](https://www.npmjs.com/package/@openlv/core)                                 | shared types and utilities                                |
| [@openlv/modal](./packages/modal) [![npm](https://img.shields.io/npm/v/@openlv/modal.svg?color=green)](https://www.npmjs.com/package/@openlv/modal)                             | solid-js modal for dApp connection management               |
| [@openlv/connector](./packages/connector) [![npm](https://img.shields.io/npm/v/@openlv/connector.svg?color=green)](https://www.npmjs.com/package/@openlv/connector)             | Wagmi connector for dApp integration                      |
| [@openlv/react-native](./packages/react-native) [![npm](https://img.shields.io/npm/v/@openlv/react-native.svg?color=green)](https://www.npmjs.com/package/@openlv/react-native) | react-native compatibility                                |
| [WIP] [extension](./packages/extension)                                                                                                                             | Browser extension for improved dApp support               |

### Rust

| Package                                                                                                                 | Description |
| ----------------------------------------------------------------------------------------------------------------------- | ----------- |
| [openlv](./crates/openlv) [![crates](https://img.shields.io/crates/v/openlv.svg?color=orange)](https://crates.io/crates/openlv) |             |
