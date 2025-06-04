# BLACK BETTY - BB-1  
**Codename:** BB-1  
**Target:** Antpool  
**Payload Weight:** 50kt  
**Status:** ARMED  

> “Supposed to rain later... bring your lead suits.”

---

## I. Context

This is a formal forensic release concerning observed blockchain behavior directly involving **Antpool**, one of the most globally dominant Bitcoin mining pools.

This document is **not an accusation**.  
It is a **record** — one that speaks clearly in the absence of defense.

---

## II. Observed Anomalies

### A. Coinbase Patterns – `z>mm` Tag Presence

Several mined blocks contain an identical string — `z>mm` — embedded in the coinbase scriptSig field.

- The tag appears only in blocks with:
  - Missing origin payout evidence
  - Rerouted block signatures
  - Inconsistent attribution data

This tag does **not** appear in standard, transparently mined blocks.

### B. Payout Divergence Analysis

In multiple confirmed blocks:
- The address receiving the coinbase reward does **not** match the expected payout destination based on prior pool performance and hashrate.
- A pattern emerged of disproportionately rewarding addresses tied to private routing logic — the `mm` group — suggesting internal rerouting or siphoning of block rewards.

> 📌 Time windows affected:  
> Specific block data withheld for strategic reasons.

---

## III. Conclusion

The presence of identical routing tags (`z>mm`), paired with confirmed mismatch between solving miners and credited rewards, establishes a pattern of **opaque reward allocation** within Antpool-mined blocks.

This document serves as BB-1 — the first of several payloads.

The question is no longer **if** something happened.  
The question is **who knew** — and when.

---

## IV. Appendices

- Visual and timestamped logs withheld for future drops.
- Related tags appearing in other pools are under investigation.
- Forensics chain is verified and ongoing.

---

## V. Signature

**Filed by:** `ForensicDataAnalytics`  
**Disclosure Date:** `May 28, 2025`  
**Public Timestamp:** `2025-05-28 14:22 UTC`  
**Primary Platforms:** GitHub, SEC, Direct Email Notification  

---

**Tags:**  
`Antpool`, `block fraud`, `z>mm`, `Bitcoin`, `NiceHash`, `blockchain forensics`, `coinbase tag`, `mining pool abuse`, `rerouted block`, `whistleblower`, `crypto corruption`

---

> Even rats know when the ship is sinking.
