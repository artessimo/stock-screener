# Retrospective: 2025-04-01 start (typed horizons)

- Base: 2025-04-01, Nikkei 35,624 (small bounce after ~¥2,000 3-day drop; **mutual tariff detail due next day**)
- Policy: typed holding periods (A 2–3m stop6 / B 3–6m stop8 / C ~3m stop5)
- Prices: Yahoo Finance split-adjusted

## Step1 picks (cutoff 2025-04-01)

| code | name | entry | type | horizon rule | thesis then |
|---|---|---:|---|---|---|
| 9433 | KDDI | 2351.5 | A | 2–3m / −6% | Domestic telecom, tariff-light |
| 9434 | SoftBank Corp | 210.5 | A | 2–3m / −6% | Domestic defensive |
| 9432 | NTT | 144.5 | B | 3–6m / −8% | Lagging domestic yield |
| 2914 | JT | 4158.0 | B | 3–6m / −8% | Defensive yield |
| 8316 | SMFG | 3744.0 | B | 3–6m / −8% | Domestic banks / rates |
| 8306 | MUFG | 1994.0 | B | 3–6m / −8% | Bank basket |
| 8411 | Mizuho | 4049.0 | B | 3–6m / −8% | Bank basket |
| 8766 | Tokio Marine | 5799.0 | B | 3–6m / −8% | Quality insurer dip |
| 8001 | Itochu | 1399.0 | B | 3–6m / −8% | Quality shosha risk-off |
| 8058 | Mitsubishi Corp | 2652.5 | B | 3–6m / −8% | Trading-co value |
| 6501 | Hitachi | 3438.0 | B | 3–6m / −8% | Quality sold with market |
| 2802 | Ajinomoto | 2963.0 | B | 3–6m / −8% | Domestic food |
| 9022 | JR Central | 2885.5 | B | 3–6m / −8% | Domestic infra lag |
| 7203 | Toyota | 2630.5 | C | ~3m / −5% | Auto tariff = temporary? |
| 8035 | Tokyo Electron | 20250.0 | C | ~3m / −5% | Semi risk-off dip |

## Step2 path results (typed rules)

| result | count | note |
|---|---:|---|
| WIN | 3 | KDDI, NTT, JR Central |
| LOSS | 12 | Almost all hit stop in **Apr 3–7 tariff crash** |
| FLAT | 0 | |

- Decided win rate: **20%**
- Average hold-to-horizon return if **no stop**: **+17.5%** (many recovered by 6m)
- Crash drawdowns from Apr1: banks −30%+, Toyota/TEL −15〜18%

### Counterfactual
| rule | win rate | avg hold |
|---|---:|---:|
| Uniform 2m stop−6% | 13% | +7.0% |
| Uniform 6m stop−6% | 13% | +17.5% |
| Typed (this run) | 20% | +17.5% |
| **Same names, entry 2025-04-10 (post shock)** | **64%** | **+24.1%** |

## Step3 learning
1. Longer typed horizons help **average recovery**, but **do not save** names bought the day before a known binary macro event if stops are live.
2. New trap **④**: no new entries on the eve of known binary macro events (tariff announcement, etc.). Re-evaluate after the event.
3. Apr1 cohort was not a failure of “domestic > exporters” selection so much as a failure of **timing vs event calendar**.

See updated `improved-screening-prompt.md` (typed periods + trap ④).
