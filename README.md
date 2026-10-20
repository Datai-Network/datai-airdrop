# $DATAI Airdrop — DATUM Campaign

Official eligibility list for the $DATAI airdrop for participants of the DATUM campaign (Crunchie + BNB Wallet Score).

| | |
|---|---|
| **Token** | $DATAI (BNB Chain) |
| **Token contract** | `0x5063eF56477935e84f953dC41A126133a9CfC294` |
| **Airdrop pool** | 400,000 $DATAI |
| **Eligible wallets** | 942 |
| **List version** | v1 — pre-appeals |
| **List file** | [`Airdrop_DATAI.csv`](./Airdrop_DATAI.csv) |
| **SHA-256** | `362097a1da8b4bc3fbd03f463bdbe2eec7667cbb4aa36538f8a22707639f1493` |
| **Appeals** | Open until [DATE] — [APPEALS FORM LINK] |
| **Claim** | Link published here after appeals close |

> ⚠️ The only official claim link will be posted on this page and on [@DATAI X HANDLE]. Datai will never DM you, and will never ask for your seed phrase or private key.

---

## How wallets were selected

84,179 wallets took part in the DATUM campaign. Earning DATUM was required to qualify, but it was not enough on its own. Every rule below was applied the same way to every wallet.

### 1. Real participation
Each wallet had to have completed **at least one quest** and linked **an X or Discord account**. Connecting a wallet without completing any quest does not count as participating.

### 2. Sybil removal
We analysed more than **750,000 recorded campaign actions**, timestamp by timestamp.

We found **769 groups of wallets acting in lockstep**. These wallets checked in during the same minutes, day after day, and ended with near-identical DATUM totals. We tested this against randomised versions of the same timelines. The real data shows **74× more synchronised wallet pairs** than chance produces, which rules out coincidence. Many of these groups also shared templated display names and accounts created minutes apart.

All **5,828 wallets** in these groups were removed.

### 3. Cap of 1,000 wallets
After filtering, the remaining wallets were ranked by DATUM, and the airdrop was capped at a maximum of 1,000 of them. The cut-off is **1,650 DATUM**, which leaves **942 eligible wallets**. The unused slots are reserved for appeals we uphold.

### 4. Distribution
The 400,000 $DATAI pool is split in proportion to the **square root** of each wallet's DATUM. A wallet that earned more DATUM receives more $DATAI, but each extra DATUM adds a little less, so no single wallet dominates.

- Allocations range from **397 to 865 $DATAI**
- Amounts are rounded to whole tokens. Any remainder goes to the wallets with the largest rounding loss, so the total is exactly 400,000. No wallet is more than 1 token away from its exact share.

### Selection funnel

| Step | Wallets remaining |
|---|---|
| All campaign wallets | 84,179 |
| At least 1 quest completed | 36,789 |
| X or Discord linked | 36,735 |
| Not in a synchronised group | 31,663 |
| At or above 1,650 DATUM — **eligible** | **942** |

Of the 5,828 wallets in synchronised groups, 756 had already been removed by steps 1–2, so this step removes 5,072 more.

---

## Appeals

If you believe your wallet was excluded in error, submit an appeal by **22/10/2026** at (https://forms.gle/qtncbyX3SqhRMzEG7)

Include:
- your wallet address
- your X and Discord handles
- any evidence of genuine, independent participation

Rules:
- Appeals are reviewed individually.
- Wallets in the same synchronised group can receive **at most one allocation per group**.
- Decisions are final.

---

## Claiming

Claims run through a **Sablier Airdrops** campaign on BNB Chain. The claim link will be added here once appeals close.

Unclaimed tokens return to the Datai treasury on **23/11/2026**.

---

## Verify the list

The SHA-256 hash above fingerprints the list file. If even one character of the file changes, the hash changes. Download the CSV and run:

```bash
# macOS
shasum -a 256 Airdrop_DATAI.csv

# Linux
sha256sum Airdrop_DATAI.csv
```

```powershell
# Windows
certutil -hashfile Airdrop_DATAI.csv SHA256
```

The output must match the hash in the table at the top. Every change to the list is recorded in this repository's commit history.

## File format

`Airdrop_DATAI.csv` has two columns:

- `address` — EIP-55 checksummed BNB Chain address
- `amount` — whole $DATAI tokens

---

## Changelog

- **v1 (pre-appeals)** — 20/10/26: initial list, 942 wallets, 400,000 $DATAI.
