<!-- Header -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=0xHimxa;Smart+Contract+Engineer;Protocol+%26+DeFi+Infrastructure;Autonomous+On-Chain+Systems" alt="Typing SVG" />
</div>

<br/>

<p align="center">
  I build autonomous on-chain protocols — prediction markets, cross-chain pricing infrastructure,<br/>
  and developer tooling that makes EVM engineering safer and faster.
</p>

<div align="center">
  <a href="https://x.com/0xhimxa">
    <img src="https://img.shields.io/badge/@0xHimxa-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
  </a>
  <a href="mailto:himxa0x@gmail.com">
    <img src="https://img.shields.io/badge/himxa0x@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://t.me/himxa">
    <img src="https://img.shields.io/badge/@Himxa-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
</div>

<br/>

<!-- Snake -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/0xHimxa/0xHimxa/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/0xHimxa/0xHimxa/output/github-contribution-grid-snake.svg"/>
    <img alt="github-snake" src="https://raw.githubusercontent.com/0xHimxa/0xHimxa/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
</div>

---

## Projects

### [SlotProbe](https://github.com/0xHimxa/SlotProbe) — EVM Storage Tooling
[![npm](https://img.shields.io/npm/v/slotprobe?color=00D9FF&style=flat-square)](https://www.npmjs.com/package/slotprobe)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

CLI tool for snapshotting, diffing, and safely migrating smart contract storage across proxy upgrades. Detects byte-range slot collisions, generates migration scripts, and auto-verifies on an Anvil fork.

```
slotprobe snapshot <address>               → named variable-level snapshot
slotprobe check-collision <old> <new>      → byte-range collision detection
slotprobe diff before.json after.json      → semantic diff at variable level
slotprobe generate-migration b.json a.json → Foundry/Hardhat script + fork verify
```

`TypeScript` · `viem` · `Foundry` · `ESM · Node ≥20`

---

### [GeoChain](https://github.com/0xHimxa/GeoChain-contrat/tree/moving-from-CPMM-to-LMSR) — Autonomous Cross-Chain Prediction Markets

LMSR prediction market protocol with no human operator. Markets are created by AI, priced by math, resolved autonomously, and kept in sync across chains via Chainlink CCIP.

```
No native EVM exp()/ln()   →  Off-chain BigInt Taylor series, validated on-chain
Dual-path price sync       →  CCIP + CRE direct writes + progressive circuit breakers
6-layer agent security     →  EIP-712 → Firestore nonce → on-chain action-mask bitfield
```

`Solidity` · `Chainlink CRE` · `CCIP` · `Foundry` · `TypeScript` · `Firebase`

---

## Stack

<div align="center">

![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink_CRE-375BD2?style=flat-square&logo=chainlink&logoColor=white)
![CCIP](https://img.shields.io/badge/Chainlink_CCIP-375BD2?style=flat-square&logo=chainlink&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=flat-square&logoColor=white)
![viem](https://img.shields.io/badge/viem-646CFF?style=flat-square&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

</div>

---

## Stats

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=0xHimxa&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xHimxa&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF&langs_count=6"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=0xHimxa&theme=tokyonight&hide_border=true&background=0D1117&stroke=00D9FF&ring=00D9FF&fire=FF6B6B&currStreakLabel=00D9FF" alt="GitHub Streak"/>
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=0xHimxa&color=00D9FF&style=flat-square&label=Profile+Views" alt="Profile views"/>
  <br/><br/>
  <sub>Open to smart contract, protocol, and DeFi infrastructure roles</sub>
</div>

