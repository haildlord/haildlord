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
  2 Years Security Research &amp; Audits &nbsp;&nbsp;|&nbsp;&nbsp; 2 Years Web3 Protocol Development
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

# Security Audits &amp; Competitive Highlights

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

# Production Protocols &amp; Smart Contracts Developed

<!-- FUTURE PROTOCOLS CAN BE SLOTTED DIRECTLY ABOVE OR BELOW THIS BLOCK -->

### TraitForge

> **Archetype:** GameFi &bull; Dynamic NFT Tokenomics &bull; Economic Honeypot  
> **Network:** **Base Mainnet** (Production)  
> **Treasury TVL:** **$10,000+ TVL locked** in DAO Fund &bull; [Basescan Proof](https://basescan.org/address/0xF99Bfb20cDe17e52424a8923f78f979C3a65eD15)  
> **Repository:** [`TraitForge/traitforge-client`](https://github.com/TraitForge/traitforge-client)

**Overview:**  
Architected the core game mechanics including bonding-curve minting pricing, generational NFT lifecycle limits, peer-to-peer secondary trading with automated protocol tax routing, and breeding/forging contracts.

<br>

<details>
<summary><b>🔍 View Deployed Smart Contracts &amp; Architecture</b></summary>

<br>

| Smart Contract | Deployed Address | Quick Lookup |
| :--- | :---: | :--- |
| [**DevFund**](https://github.com/TraitForge/traitforge-client/blob/main/lib/abis/DevFund.ts) | [`0x87F1a488229995c9c24C7C528440b21A946F36c1`](https://basescan.org/address/0x87F1a488229995c9c24C7C528440b21A946F36c1) | • Manages contributor fee allocation using a proportional weight distribution model.<br>• Accumulates ongoing protocol revenue; allows developers to withdraw earned ETH. |
| [**TraitForgeNft**](https://github.com/TraitForge/traitforge-client/blob/main/lib/abis/TraitForgeNft.ts)<br>*(NFT Contract)* | [`0xCabF9e769a9Dd211836A0e417f3f5fDF57EF2309`](https://basescan.org/address/0xCabF9e769a9Dd211836A0e417f3f5fDF57EF2309) | • Implements dynamic bonding-curve minting prices across generations.<br>• Enforces strict 10,000-entity generation caps with automatic progression. |
| [**EntityTrading**](https://github.com/TraitForge/traitforge-client/blob/main/lib/abis/EntityTrading.ts)<br>*(Marketplace)* | [`0x3a61c55bC64B34246A890F3aD5BabC4B74dAb777`](https://basescan.org/address/0x3a61c55bC64B34246A890F3aD5BabC4B74dAb777) | • Direct peer-to-peer trading protocol supporting listing, buying, and cancelling NFTs in ETH.<br>• Collects a protocol sales tax cut automatically routed into the Nuke Fund honeypot. |
| [**EntityForging**](https://github.com/TraitForge/traitforge-client/blob/main/lib/abis/EntityForging.ts)<br>*(Breeding / Forging)* | [`0xfCC74E0c0f63a6aF6A292fC3cA44C2082C138708`](https://basescan.org/address/0xfCC74E0c0f63a6aF6A292fC3cA44C2082C138708) | • Pairs listed Forgers with Mergers to generate new generational entities.<br>• Distributes forging fees between entity owners and protocol while enforcing limits.


</details>

<br><br>
<hr>
<br>

### Panoptic

> **Archetype:** DeFi &bull; Perpetual Options &bull; Permissionless Options + Lending  
> **Network:** **Ethereum Mainnet** (Production)  
> **TVL:** **~$800K in USDC** &bull; [Etherscan Proof](https://etherscan.io/address/0x00000000000E98f6c5aE16835bAdF2f7cC0d49D7)  
> **Protocol:** V2 (Uniswap v3 / v4 markets) &bull;

**Overview:**  
Panoptic is a permissionless protocol for **perpetual options** built on concentrated-liquidity AMMs (Uniswap v3/v4). Options have **no expiry** and no upfront premium. Buyers pay **streamia** (streaming premium) that accrues from real trading activity in the underlying pool, not from Black-Scholes quotes. Sellers are paid that premium for providing liquidity. Collateral is held in ERC-4626 vaults. Solvency is enforced against internal, AMM-derived price observations (spot EMA, TWAP and median oracle), so no external price feed is needed.

<br>

<details>
<summary><b>🔍 View Deployed Smart Contracts &amp; Architecture</b></summary>

<br>

| Smart Contract | Deployed Address | Quick Lookup |
| :--- | :---: | :--- |
| **PanopticPool**<br>*(`PanopticPoolV2`, core engine)* | [`0x00000000000E98f6c5aE16835bAdF2f7cC0d49D7`](https://etherscan.io/address/0x00000000000E98f6c5aE16835bAdF2f7cC0d49D7) | • Entry point for traders: `dispatch()` mints, burns and settles premium for a batch of positions in one call.<br>• `dispatchFrom()` runs liquidations, forced exercises and long-premium settlement. Which one runs depends on solvency at four ticks (spot, TWAP, latest, current) and on the position-list lengths.<br>• Mints and burns tokenized positions through the SFPM, and tracks per-chunk `s_settledTokens` and `s_grossPremiumLast` to split premium between sellers.<br>• Keeps an on-chain 8-slot median oracle (`s_oraclePack`) that anyone can update with `pokeOracle()`.<br>• Position hash (XOR of tokenIds plus a leg counter) lets users be validated without storing arrays.<br>• Deployed as a minimal clone with immutable args (CT0, CT1, RiskEngine, PoolManager, poolId, poolKey).<br>• Composable `multicall` guards: `assertTickRange`, `assertTimestampRange`, `assertBlockRange`, `assertMinCollateralValues`.<br>• Transient-storage reentrancy guard and per-tx tick-delta cap (`PriceImpactTooLarge`). |
| **CollateralTracker0**<br>*(`CollateralTrackerV2`, token0 vault)* | [`0x3E24E4Ab1e097F35C910eb9242a8C1530ee9C482`](https://etherscan.io/address/0x3E24E4Ab1e097F35C910eb9242a8C1530ee9C482) | • ERC-4626 vault and ERC-20 share token (`poXXX`) for the pool's token0. It handles deposits, withdrawals and margin accounting.<br>• Withdrawals and transfers are blocked while the user has open legs. `withdraw` with a `positionIdList` re-checks solvency first.<br>• `settleMint` and `settleBurn` charge commissions (notional fee on mint, `min(premiumFee, 10× notionalFee)` on burn) and can split them to a builder via `builderCode`.<br>• Adaptive interest model: global borrow index, per-user net borrows, and utilization-based rates computed in the RiskEngine.<br>• Interest is charged by burning shares. Insolvent users pay what they can (`InsolvencyPenaltyApplied`).<br>• Liquidation support: `delegate`/`revoke` add and remove virtual shares of `2^248−1`. `settleLiquidation` pays the bonus and realizes any protocol loss (`ProtocolLossRealized`), with minted shares capped at 10× supply.<br>• Starts with 10^6 virtual shares to blunt share-price manipulation. Supports Uniswap v4 native-ETH settlement via `unlockCallback`. |
| **CollateralTracker1**<br>*(`CollateralTrackerV2`, token1 vault)* | [`0xE1e01ac7E6b2671b82Aea4Db812a5c444523a039`](https://etherscan.io/address/0xE1e01ac7E6b2671b82Aea4Db812a5c444523a039) | • Second instance of the same vault logic, for the pool's token1.<br>• Same ERC-4626 interface, interest accrual, credited-share tracking (long amounts) and commission logic as CT0.<br>• Positions are two-sided, so solvency, premium and bonus values are tracked in both vaults at once, packed as LeftRight (token0 right slot, token1 left slot).<br>• Max deposit per call is `2^104 − 1`. Pool utilization (`assetsInAMM / totalAssets`) uses a per-tx high-water mark in transient storage, so flash deposits can't lower the rate. |
| **RiskEngine**<br>*(risk &amp; oracle logic)* | [`0x000000000000ffE5eFdB5AE76b9200263C58b4c0`](https://etherscan.io/address/0x000000000000ffE5eFdB5AE76b9200263C58b4c0) | • Stateless-for-users brain that the pool and vaults call into. Descriptions are inferred from how the pool and vaults call it.<br>• Solvency: `isAccountSolvent`, `getMargin`, `getPerPositionCollateralRequirements`. Checks happen at the ticks from `getSolvencyTicks`.<br>• Oracle: `computeInternalMedian`, `getOracleTicks`, `twapEMA`. Derives safe-mode level from deviation between ticks.<br>• Liquidations: `getLiquidationBonus`, `haircutPremia` (premium haircut before protocol loss), `exerciseCost` and `getRefundAmounts` for forced exercises.<br>• `getRiskParameters` supplies fees, max spread, max legs, buffers and dispatch tick delta, plus builder splits.<br>• Interest: `interestRate` and `updateInterestRate`.<br>• Guardian role: only it can `lockSafeMode()` or `unlockSafeMode()` on a pool. It also receives the protocol share of commissions. |
| **PanopticFactoryV3**<br>*(pool deployer)* | [`0x0000000000000aDC9A108591e718F2aee963a2a7`](https://etherscan.io/address/0x0000000000000aDC9A108591e718F2aee963a2a7) | • Likely deploys a new market: a PanopticPool clone plus its two CollateralTracker clones, then calls `initialize()` on each (inferred from the clone-with-immutable-args pattern).<br>• Initialization is one-shot and reverts with `AlreadyInitialized` on a second call.<br>• The pool's `initialize()` seeds the oracle with the current tick and sets token approvals for the SFPM and both vaults.<br>• Makes markets permissionless: anyone can open a market on a supported Uniswap pool. |

</details>

<br><br>
<hr>
<br>

# The Grind and Audits
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
