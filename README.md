
<!-- Typing SVG Header -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=0xHimxa;Smart+Contract+Engineer;Protocol+%26+DeFi+Infrastructure;Autonomous+On-Chain+Systems" alt="Typing SVG" />
</div>
 
<br/>
 
<!-- Animated divider -->
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>
 
<br/>
 
<!-- Bio -->
<p align="center">
  I build autonomous on-chain protocols — prediction markets, cross-chain pricing infrastructure,<br/>
  and agent-native DeFi systems that run <strong>without human operators</strong>.<br/><br/>
  Currently exploring cross-chain state consistency and MEV-aware pricing mechanisms.
</p>
 
<div align="center">
  <a href="mailto:himxa0x@gmail.com">
    <img src="https://img.shields.io/badge/himxa0x@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-Protocol%20%7C%20Smart%20Contract%20%7C%20DeFi-00D9FF?style=for-the-badge" alt="Open to Work"/>
</div>
 
<br/>
 
<!-- Snake animation - update the username to your actual GitHub username -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/0xHimxa/0xHimxa/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/0xHimxa/0xHimxa/output/github-contribution-grid-snake.svg"/>
    <img alt="github-snake" src="https://raw.githubusercontent.com/0xHimxa/0xHimxa/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
</div>
 
<br/>
 
---
 
## ⚙️ What I Build
 
<table>
<tr>
<td width="50%">
 
**🔢 Prediction Market Mechanisms**
LMSR pricing on the EVM with WAD-scaled (1e18) fixed-point arithmetic. `exp()` and `ln()` computed off-chain in Chainlink CRE, validated on-chain — replacing CPMM with a theoretically grounded engine.
 
</td>
<td width="50%">
 
**🌐 Cross-Chain Architecture**
Hub-spoke CCIP topology with dual-path canonical price sync and a 4-band deviation policy engine — fee surcharges, direction locks, and circuit breakers across Arbitrum and Base.
 
</td>
</tr>
<tr>
<td width="50%">
 
**🤖 Autonomous On-Chain Systems**
15+ Chainlink CRE handlers across cron, HTTP, and EVM-log triggers. Full market lifecycle automated: AI creation → resolution → dispute adjudication → LP withdrawals.
 
</td>
<td width="50%">
 
**🔐 Agent Delegation Infrastructure**
6-layer defense-in-depth for on-chain AI agent trading without custodial risk. Funds never leave the router. Agents are scoped executors — not custodians.
 
</td>
</tr>
</table>
 
---
 
## 🚀 Featured Project
 
<div align="center">
 
### [GeoChain — Autonomous Cross-Chain Prediction Markets]([https://github.com/0xHimxa/geochain](https://github.com/0xHimxa/GeoChain-contrat/tree/moving-from-CPMM-to-LMSR))
 
*An LMSR prediction market protocol where no human operator is needed.*<br/>
*Markets are created by AI, priced by math, resolved autonomously, and kept in sync across chains.*
 
</div>
 
```
No native EVM opcodes for exp()/ln()  →  Off-chain BigInt Taylor series + Halley's method
Dual-path price propagation           →  CCIP + CRE direct writes + progressive circuit breakers  
3 isolated CRE workflows              →  Automation / User Ops / Agent Trading — separate key sets
6-layer agent security model          →  EIP-712 → Firestore nonce → on-chain action-mask bitfield
```
 
<div align="center">
 
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink_CRE-375BD2?style=flat-square&logo=chainlink&logoColor=white)
![CCIP](https://img.shields.io/badge/Chainlink_CCIP-375BD2?style=flat-square&logo=chainlink&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=flat-square&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
 
</div>
 
---
 
## 📊 GitHub Stats
 
<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=0xHimxa&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xHimxa&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF&langs_count=6"/>
</div>
 
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=0xHimxa&theme=tokyonight&hide_border=true&background=0D1117&stroke=00D9FF&ring=00D9FF&fire=FF6B6B&currStreakLabel=00D9FF" alt="GitHub Streak"/>
</div>
 
---
 
## 🛠️ Core Stack
 
<div align="center">
 
| Smart Contracts | Cross-Chain | Automation | Tooling |
|:-:|:-:|:-:|:-:|
| ![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white) | ![Chainlink](https://img.shields.io/badge/CCIP-375BD2?style=for-the-badge&logo=chainlink&logoColor=white) | ![Chainlink](https://img.shields.io/badge/CRE-375BD2?style=for-the-badge&logo=chainlink&logoColor=white) | ![Foundry](https://img.shields.io/badge/Foundry-000000?style=for-the-badge&logoColor=white) |
| UUPS Proxies | Arbitrum | Cron Triggers | Forge / Anvil |
| EIP-712 | Base | HTTP Triggers | TypeScript |
| Fixed-Point Math | Multi-chain | EVM Log Triggers | Firebase |
 
</div>
 
---
 
## 📡 Currently
 
```solidity
string public building   = "LMSR prediction markets with autonomous CRE workflows";
string public exploring  = "Cross-chain state consistency + MEV-aware pricing";
string public openTo     = "Smart contract, protocol, and DeFi infrastructure roles";
```
 
<br/>
 
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=0xHimxa&color=00D9FF&style=flat-square&label=Profile+Views" alt="Profile views"/>
</div>
 
<!-- 
=============================================================
SETUP INSTRUCTIONS — remove this comment block before publishing
=============================================================
 
1. SNAKE ANIMATION — requires a GitHub Actions workflow.
   Create .github/workflows/snake.yml in your profile repo (0xHimxa/0xHimxa):
 
   name: Generate Snake
   on:
     schedule:
       - cron: "0 */12 * * *"
     workflow_dispatch:
   jobs:
     generate:
       runs-on: ubuntu-latest
       steps:
         - uses: Platane/snk@v3
           with:
             github_user_name: ${{ github.repository_owner }}
             outputs: |
               dist/github-contribution-grid-snake.svg
               dist/github-contribution-grid-snake-dark.svg?palette=github-dark
         - uses: crazy-max/ghaction-github-pages@v3
           with:
             target_branch: output
             build_dir: dist
           env:
             GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
 
2. GITHUB STATS — replace 0xHimxa with your actual GitHub username
   in the stats card URLs if it differs.
 
3. STREAK STATS — same, replace username in the streak stats URL.
 
4. All services used (free, no API key needed):
   - https://readme-typing-svg.demolab.com
   - https://github-readme-stats.vercel.app
   - https://github-readme-streak-stats.herokuapp.com
   - https://komarev.com/ghpvc/
Open to — smart contract, protocol, and DeFi infrastructure roles
