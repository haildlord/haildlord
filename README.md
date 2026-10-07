<div align="center">
  <img src="./lords_banner.jpeg" width="100%" alt="Banner"/>
</div>

<br><br>

<div align="center">
  <h1 style="margin-bottom: 8px;">
    Hail The Lord 🔱
  </h1>

  <h3 style="margin-top: 0; color: #888;">
    Smart Contract Developer &amp; Security Researcher
  </h3>

  <p>
    <a href="https://x.com/hail_d_lord">
      <img src="https://img.shields.io/badge/X-black?style=flat&logo=x&logoColor=white" alt="X"/>
    </a>
    &nbsp;&nbsp;
    <a href="mailto:hailthelord16@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white" alt="Gmail"/>
    </a>
    &nbsp;&nbsp;
    <a href="https://t.me/hail_d_lord">
      <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram"/>
    </a>
  </p>

  <br>

  <p>
    <strong>Solidity &nbsp;&bull;&nbsp; Rust &nbsp;&bull;&nbsp; Ethereum &nbsp;&bull;&nbsp; Solana</strong>
    <br><br>
    Foundry &bull; Hardhat &bull; Anchor &bull; Huff &bull; EVM Opcodes
  </p>
</div>

<br><br>

<div align="center">
  <h2>
    🛡️ 2 Years Security Research &amp; Audits &nbsp;&nbsp;|&nbsp;&nbsp; 🛠️ 2 Years Web3 Protocol Development
  </h2>
</div>

<br>

<div>
  <p style="max-width: 680px; margin: 0 auto; text-align: left; line-height: 1.7;">
    My engineering and security mindset wasn't built overnight—it was forged through years of <strong>Competitive Programming and C++</strong>.
    <br><br>
    While building trading systems for 4 years, I applied the rigor of <strong>DSA (Data Structures &amp; Algorithms)</strong> to every line, constantly hunting for the one edge case that could break the system.
    <br><br>
    Over the past 2 years, I have translated that precision into shipping production-grade smart contracts (GameFi, dynamic NFT tokenomics, and decentralized liquidity engines) alongside <strong>Full-Time Smart Contract Security Research</strong>. By bridging protocol architecture with an adversarial audit mindset, I spot deep logic flaws, invariant breaks, and complex economic attack vectors that automated tools miss.
  </p>
</div>

<br><br>
<hr>
<br>

# 🏆 Security Audits &amp; Competitive Highlights

<br>

| Protocol / Engagement | Type | Ecosystem | Concept | Findings | Report | Rank |
| :--- | :---: | :---: | :--- | :---: | :---: | :---: |
| **Phi** | Public | Ethereum | Onchain identity | 4 H, 2 M | [Report](https://code4rena.com/reports/2024-08-phi) | [15](https://code4rena.com/audits/2024-08-phi) |
| **Telcoin-Network** | Public | Ethereum | Narwhal &amp; Bullshark + Axelar | 1 H | Private | [46](https://cantina.xyz/code/26d5255b-6f68-46cf-be55-81dd565d9d16/overview/leaderboard?search=hail) |
| **TraitForge** | Public | Ethereum | NFT game + rewards | 1 H, 3 M | [Report](https://code4rena.com/reports/2024-07-traitforge) | [86](https://code4rena.com/audits/2024-07-traitforge) |
| **Virtuals Protocol** | Public | Ethereum | Co-ownership of AI agents | 1 H | [Report](https://code4rena.com/reports/2025-04-virtuals-protocol) | [92](https://code4rena.com/audits/2025-02-virtuals-protocol) |
| **RAAC** | Public | Ethereum | Real estate + Finance rails | 1 H, 2 M | [Report](https://codehawks.cyfrin.io/c/2025-02-raac/results?t=report) | [111](https://codehawks.cyfrin.io/c/2025-02-raac/results?page=12) |
| **Mystic Finance** | Private | Ethereum | Deposit &amp; Rewards | 2 M | [Report](https://github.com/Kann-Audits/Kann-Audits/blob/main/reports/pdf-format/Mystic%20Finance.pdf) | Private |

<br><br>
<hr>
<br>

# 🚀 Production Protocols &amp; Smart Contracts Developed

<!-- FUTURE PROTOCOLS CAN BE SLOTTED DIRECTLY ABOVE OR BELOW THIS BLOCK -->

### 🎮 TraitForge

> **Archetype:** GameFi &bull; Dynamic NFT Tokenomics &bull; Economic Honeypot  
> **Network:** **Base Mainnet** (Production)  
> **Treasury TVL:** **$10,000+ TVL locked** in DAO Fund &bull; [Basescan Proof](https://basescan.org/address/0xF99Bfb20cDe17e52424a8923f78f979C3a65eD15)  
> **Repository:** [`TraitForge/traitforge-client`](https://github.com/TraitForge/traitforge-client)

**Overview:**  
Architected a 12-contract GameFi ecosystem featuring dynamic bonding-curve minting prices, deterministic on-chain genetics/entropy, breeding and merging loops, and a self-balancing game-theory honeypot (Nuke Fund).

<br>

<details>
<summary><b>🔍 View Deployed Smart Contracts &amp; Architecture (12 Contracts)</b></summary>

<br>

| Contract | Type / Role | Onchain Proof | Details |
| :--- | :--- | :---: | :--- |
| **`TraitForgeNft`** | Core ERC-721 Engine | [`0xCabF...`](https://basescan.org/address/0xCabF9e769a9Dd211836A0e417f3f5fDF57EF2309) | • Implements dynamic bonding-curve minting prices across generations.<br>• Enforces strict 10,000-entity generation caps with automatic progression. |
| **`EntropyGenerator`** | Deterministic Randomness | [`0x3124...`](https://basescan.org/address/0x31248a94C8ec87991834f175b1454D4e0E16D0A0) | • Derives 13-digit pseudo-random entropy values governing entity roles and traits.<br>• Computes hereditary blended entropy for bred offspring entities (`getInbredEntropy`). |
| **`EntityForging`** | Breeding / Merging Protocol | [`0xfCC7...`](https://basescan.org/address/0xfCC74E0c0f63a6aF6A292fC3cA44C2082C138708) | • Pairs listed Forgers with Mergers to generate new generational entities.<br>• Distributes forging fees between entity owners and protocol while enforcing limits. |
| **`EntityTrading`** | Native P2P Marketplace | [`0x3a61...`](https://basescan.org/address/0x3a61c55bC64B34246A890F3aD5BabC4B74dAb777) | • Direct peer-to-peer trading protocol supporting listing, buying, and cancelling NFTs in ETH.<br>• Collects a protocol sales tax cut automatically routed into the Nuke Fund honeypot. |
| **`NukeFund`** | Central Honeypot Fund | [`0xb663...`](https://basescan.org/address/0xb66344cAFaA61d15b7cd6cC68B3BBaADffAbd235) | • Central economic pool accumulating ETH from minting, forging, and marketplace taxes.<br>• Lets players burn ("nuke") eligible entities to claim a proportional share of the pot. |
| **`LottFund`** | Chainlink VRF Lottery | [`0x92ac...`](https://basescan.org/address/0x92ac212CBc1B23d66eEaCEFB7993520187Bc6293) | • Round-based jackpot system using Chainlink VRF for provably fair onchain drawings.<br>• Manages batch bidding, distributes jackpot pools to winners, and routes revenue splits. |
| **`Trait`** | ERC-20 Utility Token | [`0xd304...`](https://basescan.org/address/0xd304C83b6b7153E3B71d7f24dA15Dd9615497979) | • Native ecosystem currency with controlled minting, burn, and emergency pausability.<br>• Distributed via airdrops and integrated across community incentives and DAO reserves. |
| **`DAOFund`** | Ecosystem Treasury | [`0xF99B...`](https://basescan.org/address/0xF99Bfb20cDe17e52424a8923f78f979C3a65eD15) | • Protocol treasury holding **$10,000+ TVL** for decentralized governance.<br>• Connected to Uniswap V2 router for automated protocol liquidity and token swaps. |
| **`DevFund`** | Weighted Reward Vault | [`0x87F1...`](https://basescan.org/address/0x87F1a488229995c9c24C7C528440b21A946F36c1) | • Manages contributor fee allocation using a proportional weight distribution model.<br>• Accumulates ongoing protocol revenue; allows developers to withdraw earned ETH. |
| **`Airdrop`** | Distribution Vault | [`0x8f1D...`](https://basescan.org/address/0x8f1D2e2049A9FC72cE4CDA4eC3b920CBb108eb1B) | • Manages allocations of `Trait` tokens to early players and whitelist participants.<br>• Tracks user claim states (`userInfo`) with pause and access-control protection. |
| **`NukeRouter`** | Transaction Router | [`0x3519...`](https://basescan.org/address/0x35192165759556e3E150De2b31ad39F8aaC4F6d4) | • Intermediary router batching approvals and contract interactions into atomic calls.<br>• Streamlines multi-step player interactions with the Nuke Fund to optimize UX and gas. |
| **`PriceOracle`** | Chainlink Feed Adapter | [`0x694A...`](https://sepolia.etherscan.io/address/0x694AA1769357215DE4FAC081bf1f309aDC325306) | • Interfaces with Chainlink's ETH/USD aggregator for real-time market data.<br>• Powers frontend conversions for dynamic mint pricing and real-time USD fiat valuations. |

</details>

<br><br>
<hr>
<br>

# ⚔️ The Grind and Audits
*A log of public contests where I sharpened my pattern recognition and understanding of complex logic.*

<br>

| Contest | Ecosystem | Concept Encountered | The Lesson (Struggle &amp; Growth) |
| :--- | :--- | :--- | :--- |
| **Flying Tulip** | Ethereum | Spot trading, lending, perps, insurance | **The Complexity Test.** Balanced multiple financial primitives simultaneously. Found 5 bugs during the judging phase. |
| **Ekubo** | Ethereum | **Transient Storage (EIP-1153)**, Till Pattern | **The Assembly Hurdle.** The heavy use of low-level assembly initially confused me. I forced myself to learn the "Till" structure, unlocking a new angle of viewing code. |
| **Megapot** | Ethereum | **On-Chain Entropy**, Randomness | **Refining Process.** My first successful "Shadow Audit." I focused entirely on audit structure rather than just finding bugs, improving my reporting clarity. |
| **Ammalgam** | Ethereum | **Capital Efficiency**, Lending + Trading Math | **Methodology Overhaul.** Spent 2 months reviewing mistakes here. Redemption: Later found a Medium bug during a shadow audit that 100+ wardens missed. |
| **Covenant** | Ethereum | **Leverage**, Credit Multipliers | **Managing Anxiety.** Learned to treat audits like an exam: skip the hard parts, keep moving, and don't panic if the code is clean. |
| **Hybra** | Ethereum | **Hyperliquid L1**, Liquidity Layers | **Code > Docs.** Wasted days reading documentation that confused me. Taught me to ignore the noise and read the codebase first to build my own mental model. |
| **Plaza** | Ethereum | **Dual-Token Economics** | **Economic Logic.** Shifted my focus from syntax errors to high-level economic de-pegging risks and leverage-backed token mechanics. |
| **Burve** | Ethereum | **Uniswap V3 Deep Dive**, Multi-Swap | **The Deep Dive Trap.** Took 1 month off just to master UniV3 internals after failing to grasp the protocol interaction during the audit. Now I know it by heart. |
| **Biconomy** | Ethereum | **ERC-4337**, Account Abstraction | **Complexity Shock.** The assembly-heavy logic was a humbling check on how much I still had to learn about EVM internals. |
| **Hypovault** | Ethereum | **Options Strategies**, DeFi Derivatives | **Scope Paralysis.** Learned to draw hard boundaries on what to read after wasting time on the parent codebase instead of the specific scope. |
| **Usual** | Ethereum | **Stablecoin**, RWA Backing | **The Rules of the Game.** Submitted 4 bugs that were disqualified. A harsh lesson in understanding specific platform judging rules (Sherlock). |
