<div align="center">

  # SATOSYS

  **Satoshi Systems Technology** &nbsp;|&nbsp; [satosys.tech](https://satosys.tech)

  *Building the physical and digital infrastructure for a Bitcoin standard.*

  [![bitpos.app](https://img.shields.io/badge/bitpos.app-live-F7931A?style=flat-square&logo=bitcoin&logoColor=white)](https://bitpos.app)&nbsp;
  [![License: MIT](https://img.shields.io/badge/MIT-open_source-3178C6?style=flat-square)](https://github.com/satosys-tech/bitpos-core/blob/main/LICENSE)&nbsp;
  [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/satosys-tech/bitpos-core)

  </div>

  ---

  ## bitPOS

  Lightning point-of-sale and Bolt Card wallet. Accept instant payments. Issue NFC tap-to-pay cards. Run a full POS terminal. On Bitcoin.

  **[bitpos.app](https://bitpos.app)** - hosted. Operational in minutes.
  **[bitpos-core](https://github.com/satosys-tech/bitpos-core)** - self-hosted. Your server. Your keys.

  Both paths run the same code.

  ---

  ## Repositories

  | Repo | Description |
  |------|-------------|
  | [**bitpos-core**](https://github.com/satosys-tech/bitpos-core) | Lightning POS server + PWA. Express, PostgreSQL, NWC integration, Bolt Card LNURLw. Single Docker container. MIT. |
  | [**bitpos-card-writer**](https://github.com/satosys-tech/bitpos-card-writer) | Android app for programming NTAG 424 DNA Bolt Cards. Full AES-128 key personalization over raw NFC APDU. [Download APK.](https://github.com/satosys-tech/bitpos-card-writer/releases/latest) |

  ---

  ## Stack

  ```
  Lightning     Nostr Wallet Connect (NWC) - works with any compatible wallet, no custodian
  Cards         NTAG 424 DNA - AuthEV2First, ChangeKey x5, SDM via raw APDU
  Backend       TypeScript / Express / PostgreSQL / Drizzle ORM
  Frontend      React / Vite / PWA - installable, works offline
  Mobile        Expo / React Native / react-native-nfc-manager
  Deploy        Docker - single container with embedded Postgres, or external DB
  ```

  ---

  ## Self-host

  ```bash
  curl -sSL https://bitpos.app/install.sh | bash
  ```

  Docker 24+. An NWC-compatible wallet. That's it.

  ---

  <div align="center">

  [satosys.tech](https://satosys.tech) &nbsp;|&nbsp; [bitpos.app](https://bitpos.app) &nbsp;|&nbsp; satosys.tech@gmail.com

  </div>
  