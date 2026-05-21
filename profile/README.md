<div align="center">

  # SATOSYS

  **Satoshi Systems Technology**

  *Building physical and digital infrastructure for a Bitcoin standard.*

  [![Website](https://img.shields.io/badge/satosys.tech-orange?style=flat-square&logo=bitcoin&logoColor=white)](https://satosys.tech)
  [![Product](https://img.shields.io/badge/bitpos.app-live-brightgreen?style=flat-square)](https://bitpos.app)
  [![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/satosys-tech/bitpos-core/blob/main/LICENSE)

  </div>

  ---

  ## What we build

  We make Lightning payments infrastructure. Point-of-sale terminals, Bolt Card issuance, self-custodial wallets - all on Bitcoin.

  **[bitpos.app](https://bitpos.app)** is our hosted product: a fully managed Lightning POS and Bolt Card wallet you can use in minutes.

  **[bitpos-core](https://github.com/satosys-tech/bitpos-core)** is the open-source engine that powers it. The same code runs in production at bitpos.app - you can verify every line.

  ---

  ## The open-core model

  We follow the pattern established by projects like BoltCard/CoinCorner: open the core, run the service.

  - The full server, database schema, NFC card logic, and PWA are MIT-licensed and auditable
  - `docker run` and you have a production-ready instance in under a minute
  - bitpos.app exists for operators who want zero DevOps - same software, managed by us

  This is not a bait-and-switch. The OSS version is not crippled. We open the code because we believe software that holds Bitcoin should be verifiable by anyone.

  ---

  ## Repositories

  | | Repo | What it is |
  |---|------|-----------|
  | ![TypeScript](https://img.shields.io/badge/-TS-3178C6?style=flat-square&logo=typescript&logoColor=white) | [bitpos-core](https://github.com/satosys-tech/bitpos-core) | Self-hosted Lightning POS + Bolt Card wallet. Express + PostgreSQL + Docker. NWC-powered. |
  | ![Android](https://img.shields.io/badge/-APK-3DDC84?style=flat-square&logo=android&logoColor=white) | [bitpos-card-writer](https://github.com/satosys-tech/bitpos-card-writer) | Android app for programming NTAG 424 DNA Bolt Cards. Full APDU sequence in TypeScript. |

  ---

  ## Technical stack

  ```
  Lightning layer    Nostr Wallet Connect (NWC) - works with any NWC-compatible wallet
  Card protocol      NTAG 424 DNA - full AuthEV2First + ChangeKey + SDM APDU sequence
  Backend            TypeScript / Express / PostgreSQL / Drizzle ORM
  Frontend           React / Vite / PWA
  Mobile             Expo / React Native / react-native-nfc-manager
  Infrastructure     Docker - single container with embedded Postgres or external DB
  ```

  ---

  ## Self-host in 60 seconds

  ```bash
  curl -sSL https://bitpos.app/install.sh | bash
  ```

  Requires Docker and an NWC-compatible wallet ([Alby Hub](https://albyhub.com) recommended).

  ---

  ## Just want it to work?

  **[Sign up at bitpos.app](https://bitpos.app)** - no server, no DevOps, no key management.

  ---

  <div align="center">

  [satosys.tech](https://satosys.tech) &nbsp;|&nbsp; [bitpos.app](https://bitpos.app) &nbsp;|&nbsp; satosys.tech@gmail.com

  *We don't build on sand.*

  </div>
  