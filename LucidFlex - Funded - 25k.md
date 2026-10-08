---
prop: Lucid
tipo: LucidFlex
fase: Funded
taglio: "25.000 $"
target: "nessuno"
mll: "1.000 $"
dd_tipo: EOD
dd_dettaglio: "EOD: traila fino a 26.100, poi blocca a 25.100; dopo il payout l'MLL si adegua al Locked"
consistency: off
daily_loss: "600 $ (se eval ON) / none (se eval OFF)"
scaling_plan: "yes (tier per profitto)"
days_to_payout: "nessun window fisso"
min_profit_days: "5 giorni con ≥ 100 $"
payout: "min 500 $ · max 50% profit fino a 1.000 $ · 5 payout poi live · split 90/10"
payouts_to_live: 5
time_limit: 0
max_contratti: "2 mini / 20 micro (scaling)"
costo: 
strumenti: "mini/micro CME"
stato: da-verificare
---

# Lucid — LucidFlex — Funded — 25k

## Regole

| Voce | Valore |
| --- | --- |
| Target | nessuno (nessuna soglia fissa) |
| Max Loss (MLL) | 1.000 $ |
| Tipo drawdown | **EOD** — traila fino a **26.100**, poi blocca a **25.100** |
| DLL (below initial trial) | 600 $ se eval ON · none se OFF |
| Consistency | **nessuna** |
| Min days of profit | **5 giorni ≥ 100 $** |
| Payout | min 500 $ · max 50% profit fino a **1.000 $** · fino a 5 poi live · split 90/10 |
| Days to payout | nessun window fisso |
| Scaling plan | **Sì** (tier per profitto) |
| Max size | 2 mini / 20 micro |

## Note

- Requisiti payout: **5 giorni con ≥100 $** + **netto positivo** nel ciclo.
- DLL: **carry-over dall'eval** → se in eval DLL ON, nel funded il DLL (below initial trial) è attivo; se OFF, none.
