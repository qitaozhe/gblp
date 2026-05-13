> **📢 征询意见稿** – 本文件为公开讨论草案，不代表最终定稿。欢迎通过 Issue 或 PR 提出修改建议。

# Technical Whitepaper (Summary) – GBLP v0.1

## 1. Identity & Wallet

- **DID + biometrics + social recovery**.
- Users generate a DID offline; biometric hash stored locally. 5 guardians for key recovery.
- For undocumented persons: temporary DID after three community witnesses → permanent after 2 years.

## 2. Survival Line & Basic Unit Amount

- Survival line = minimum cost of food, water, shelter, healthcare, basic internet (monthly).
- Regional data from FAO, WHO, and local statistics.
- **Basic Unit Amount = 80% of survival line** (below subsistence).

## 3. Anti-Reselling Mechanism

- Basic units can only be spent at approved MCC codes (groceries, utilities, basic medicine).
- Fraud detection AI flags abnormal patterns (e.g., many wallets spending basic units at same terminal).
- **Penalties** (progressive, capped at 6 months):
  - 1st offence: Current month’s units forfeited, half to whistleblower.
  - 2nd: 1-month suspension
  - 3rd: 2-month suspension
  - 4th: 4-month suspension
  - 5th+: 6-month suspension (reset after full term)
- Appeals: Arbitration tribunal (3 tech experts + 2 citizen observers).

## 4. Real-Goods Aid Vouchers

- Donor pledges goods (new or 80%+ functional during crises).
- Random inspection by 3 independent nodes (NGOs, universities).
- If verified, an NFT voucher is minted and distributed to EBWs of recipients.
- Voucher redeemed at local warehouse → NFT burned.
- Penalties: false declaration → shipment returned at donor’s expense; 3 strikes → 12-month ban on goods aid.

## 5. Technical Resistance to State-Level Blockade

- Offline p2p sync via Bluetooth mesh and satellite broadcast.
- If a government cuts internet, EBW clients switch to offline mode and still validate.
- “Protected hibernation”: if 90% of connections from a country drop for >48h, wallet state frozen but preserved. When connection resumes, all missed units are backfilled.
- Sanctions against blocking government (see charter).

## 6. Global Settlement Coin (GSC) – High-Level

- Minting: anyone can lock a verified basket of physical goods (via IoT warehouse receipts) to mint GSC.
- Redemption: burn GSC to claim the underlying goods.
- GSC supply expands/contracts with real economic activity – no arbitrary inflation.
- Central Bank Alliance nodes validate each mint/burn; consensus (BFT) on state.

## 7. Exchange Pool (Regional ↔ GSC)

- Each region operates a liquidity pool collateralized by GSC.
- Exchange rate = algorithm based on region’s CPI, unemployment, fiscal deficit, and pool depth.
- A 0.1% “solidarity tax” is deducted on each exchange to fund the EBW.
## 8. Eternal Coin Index

To quantify the principles of “Integrity of Earth, Safety of Humanity, Permanence of Public Trust”, the system computes a real‑time composite index called the **Ξ‑Index** (Eternal Coin Index), ranging from 0 to 100. The formula is:
