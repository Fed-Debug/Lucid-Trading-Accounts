---
prop: Lucid
tipo: LucidDaily
fase: Funded
taglio: "25.000 $"
target: "nessuno"
mll: "1.000 $"
dd_tipo: Intraday
dd_dettaglio: "Intraday: traila fino a 26.100, poi blocca a 25.100"
consistency: off
daily_loss: "none"
buffer: "26.100"
max_daily_profit: "6.000 $"
max_contratti: "2 mini / 20 micro"
payout: "daily · min 500 $ · max = profitti sopra buffer · 90/10"
activation_fee: "nessuna"
strumenti: "mini/micro CME"
stato: ufficiale
---

# Lucid — LucidDaily — Funded — 25k

## Regole

| Voce | Valore |
| --- | --- |
| Target | nessuno (payout sopra buffer) |
| Max Loss (MLL) | 1.000 $ |
| Tipo drawdown | **Intraday** (sempre) — traila fino a **26.100**, poi blocca a **25.100** |
| Buffer per payout | **26.100 $** (MLL + 100) |
| Daily Loss Limit | **none** (scelta eval: DLL OFF) |
| Consistency | **nessuna** |
| Payout | **daily** · min 500 $ · max = profitti sopra buffer · 90/10 |
| Max daily profit | 6.000 $ → poi **live** |
| Account Activation fee | nessuna |
| Max size | 2 mini / 20 micro |

## Note

- Le funded rules **non cambiano** in base alla combinazione scelta in eval (DD sempre Intraday).
- **News trading**: vietato (high impact USD) → hard breach.
