# ⚽ Timestamped Football Odds incl. Pinnacle — 90 Competitions Worldwide: 5 Packs in One (free sample)

**Timestamped Soccer World All-in-One Premium — free sample: 20 matches out of 197,615, from 17 of the 90 competitions.**
Same tables, same columns, same formats as the full product, one file per competition of the sample.

Most football odds datasets give you one closing number per match. The full product gives you
**353,573,942 timestamped quotes** from 5 named bookmakers, pre-match and in-play, with the score
and the match clock the bookmaker sent on its in-play quotes, plus the opening and the closing of every book and
market with the exact time each was recorded, and 10,835,875 dated snapshots from 37 more bookmakers.

**90 competitions, one schema:** the top flights of 66 countries, the second divisions of England, Spain, Italy, Germany, France and Portugal, and
18 international competitions for clubs and national teams, from the Champions League and the Copa Libertadores to the World Cup.

⚽ **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/ylkgqx?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=readme_top)** — 197,615 matches, 90 competitions, 898 competition-seasons, 2016–2026.

---

## In this repository

| Path | What it is |
|---|---|
| `sample/` | The free 20-match sample: same tables, same columns as the full product |
| `Ultimate_Verify_Before_You_Buy.ipynb` | *Verify before you buy*: the key figures of the listing recomputed on the **full** product, outputs included |

Also on [Hugging Face](https://huggingface.co/datasets/oliviersportsdata/World-Football-Timestamped-Odds-Pinnacle-Match-Stats), with a table viewer, and on [Kaggle](https://www.kaggle.com/datasets/oliviersportsdata/world-football-odds-with-pinnacle-sample).

---

## Five packs in one

| Pack (also sold on its own) | Competitions | Matches | Timestamped quotes | Period |
|---|---:|---:|---:|---|
| [Big 6 Europe Premium](https://sportsdataolivier.gumroad.com/l/uooqdc?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=pack_table) — England, Spain, Italy, Germany, France, Portugal, 2 divisions each | 12 | 45,554 | 87,379,474 | 2016-08-28 to 2026-09-28 |
| [Other European Leagues Premium](https://sportsdataolivier.gumroad.com/l/aplpqd?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=pack_table) — 44 top flights of Europe | 44 | 92,615 | 132,116,120 | 2016-08-28 to 2026-09-29 |
| [International Football Premium](https://sportsdataolivier.gumroad.com/l/hethzg?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=pack_table) — Champions League to World Cup, 18 competitions | 18 | 11,118 | 28,943,376 | 2016-08-31 to 2026-09-29 |
| [Futbol, Futebol & Soccer Premium](https://sportsdataolivier.gumroad.com/l/diswpw?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=pack_table) — 9 top flights of the Americas | 9 | 30,999 | 73,680,541 | 2016-08-28 to 2026-09-30 |
| [Timestamped Soccer Asia & Africa Premium](https://sportsdataolivier.gumroad.com/l/gxvqou?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=pack_table) — 7 top flights of Asia and Africa | 7 | 17,329 | 31,454,431 | 2016-08-28 to 2026-09-27 |

This product merges the five into one schema: the same columns for all 90 competitions, one `Match_ID` key
across all of them.

---

## What's in this sample

| Table | Sample | Full product |
|---|---:|---:|
| Odds_Timestamped | 55,392 | 353,573,942 |
| Minute_Stats | 11,144 | 49,494,435 |
| Bookmaker_Snapshots | 1,554 | 10,835,875 |
| Lineups | 834 | 5,478,267 |
| Events | 1,165 | 5,220,292 |
| Team_Stats | 40 | 395,230 |
| Opening_Closing | 20 | 197,615 |
| Matches | 20 | 197,615 |

The 20 matches: two finals that went to penalties (the 2022 World Cup and the 2026 Champions League, the latter
shown quote by quote below), the EURO 2024, Copa Libertadores 2025, Club World Cup 2025 and MLS Cup 2025 finals, Saudi
Arabia's win over Argentina at the 2022 World Cup, the derbies of Madrid-Barcelona, Bayern-Dortmund, Glasgow,
Istanbul, Amsterdam-Rotterdam, Buenos Aires, Rio, Riyadh and Casablanca, the J1 100 Year Vision League final and a
14-13 shoot-out in Japan, and two Premier League matches of September 2026. 2 went to extra time, 3 to a
penalty shoot-out.

| Pack | Competition | Season | Stage | Date (UTC) | Match | Result | Note |
|---|---|---|---|---|---|---|---|
| Big 6 Europe | Bundesliga | 2025/26 | Regular Season, matchday 24 | 2026-02-28 | Borussia Dortmund – Bayern Munich | 2-3 | Der Klassiker |
| Big 6 Europe | La Liga | 2025/26 | Regular Season, matchday 35 | 2026-05-10 | Barcelona – Real Madrid | 2-0 | El Clasico |
| Big 6 Europe | Premier League | 2026/27 | Regular Season, matchday 5 | 2026-09-20 | Man City – Sunderland | 5-3 | recent match: Premier League, 20 September 2026 |
| Big 6 Europe | Premier League | 2026/27 | Regular Season, matchday 5 | 2026-09-20 | Fulham – Man Utd | 1-1 | recent match: Premier League, 20 September 2026 |
| Other European Leagues | Eredivisie | 2025/26 | Regular Season, matchday 28 | 2026-03-22 | Feyenoord – Ajax | 1-1 | De Klassieker |
| Other European Leagues | Super Lig | 2025/26 | Regular Season, matchday 31 | 2026-04-26 | Galatasaray – Fenerbahce | 3-0 | Istanbul derby |
| Other European Leagues | Scottish Premiership | 2026/27 | Regular Season, matchday 7 | 2026-09-20 | Celtic – Rangers | 0-1 | Old Firm derby |
| International | FIFA World Cup | 2022 | Group Stage, matchday 1 | 2022-11-22 | Argentina – Saudi Arabia | 1-2 | World Cup group stage: Saudi Arabia beat Argentina |
| International | FIFA World Cup | 2022 | Final | 2022-12-18 | Argentina – France | 2-2 · 3-3 aet · 4-2 pens | World Cup 2022 final: extra time, then penalties |
| International | UEFA European Championship | 2024 | Final | 2024-07-14 | Spain – England | 2-1 | EURO 2024 final |
| International | FIFA Club World Cup | 2025 | Final | 2025-07-13 | Chelsea – PSG | 3-0 | Club World Cup final 2025 |
| International | Copa Libertadores | 2025 | Final | 2025-11-29 | Palmeiras – Flamengo | 0-1 | Copa Libertadores final 2025 |
| International | UEFA Champions League | 2025/26 | Final | 2026-05-30 | PSG – Arsenal | 1-1 · 1-1 aet · 4-3 pens | Champions League final 2026: extra time, then penalties; shown quote by quote |
| Americas | Major League Soccer | 2025 | Final | 2025-12-06 | Inter Miami CF – Vancouver Whitecaps | 3-1 | MLS Cup final 2025 |
| Americas | Campeonato Brasileiro Serie A | 2026 | Regular Season, matchday 11 | 2026-04-12 | Fluminense – Flamengo | 1-2 | Fla-Flu derby |
| Americas | Argentine Primera Division | 2026 | Group Stage, matchday 15 | 2026-04-19 | River Plate – Boca Juniors | 0-1 | Superclasico |
| Asia & Africa | J1 League | 2026 | Group Stage, matchday 8 | 2026-03-21 | Avispa Fukuoka – Gamba Osaka | 2-2 · 14-13 pens | J1 100 Year Vision League: draw after 90 minutes, shoot-out 14-13 |
| Asia & Africa | Botola Pro | 2025/26 | Regular Season, matchday 20 | 2026-05-09 | Raja Casablanca – WAC Casablanca | 0-1 | Casablanca derby |
| Asia & Africa | Saudi Pro League | 2025/26 | Regular Season, matchday 32 | 2026-05-12 | Al-Nassr Riyadh – Al Hilal Riyadh | 1-1 | Riyadh derby |
| Asia & Africa | J1 League | 2026 | Final, leg 2 | 2026-06-06 | Kashima Antlers – Vissel Kobe | 2-0 · agg 2-5 | J1 100 Year Vision League final, second leg |

Season and stage on every match; matchday on 92.3 % of the full product's matches (where the source's
numbering is reliable) and leg on every two-legged tie. `Ultimate_Coverage.csv` (in this sample too) gives the
coverage of the full product, competition by competition and season by season.

---

## Book coverage (full product)

Coverage is not uniform. Here is what each book actually priced.

| Book | Quotes | Matches with an FT 1X2 close | First FT 1X2 close | Closing prices on |
|---|---:|---:|---|---|
| Bet365 | 250,606,072 | 191,146 (96.7 %) | 2016-08-28 | all 8 markets |
| Pinnacle | 17,177,038 | 145,004 (73.4 %) | 2018-09-27 | 1X2, total goals; Asian handicap from Jun 2023 |
| Unibet | 23,263,098 | 166,824 (84.4 %) | 2017-04-15 | 1X2, total goals |
| Betfair (Sportsbook) | 54,134,487 | 37,412 (18.9 %) | 2023-11-03 | 1X2 |
| Betsson | 8,393,247 | 73,034 (37.0 %) | 2022-07-03 | 1X2, total goals |

Split: **263,916,151 in-play** (74.6 %) · **89,657,791 pre-match** (25.4 %).

Markets: full-time 1X2, Asian handicap, total goals and total corners, and the same four for the
first half. Bookmakers are always named, never aggregated. The 37 other bookmakers are in
`Bookmaker_Snapshots`: their first and last pre-match snapshot, each with its time.

### Coverage over time

A bookmaker, or a table, is not in the source for the whole period. Computed month by month on the full product:

| Source | From | Gaps (months when fewer than half of the matches have it) | Stops for |
|---|---|---|---|
| Bet365 | 2016-08-28 | none | BLR (after 2021-11-28), RUS (after 2022-03-07) |
| Pinnacle | 2018-09-27 | 2023-09 to 2023-11, 2026-07 to 2026-08 | - |
| Unibet | 2017-04-15 | 2026-07 to 2026-08 | BLR (after 2021-11-28), MNE (after 2022-05-20), RUS (after 2022-03-07) |
| Betfair (Sportsbook) | 2023-11-03 | 2024-11 to 2025-08, 2026-07 to 2026-08 | - |
| Betsson | 2022-07-03 | 2026-06 to 2026-08 | - |
| Minute-by-minute statistics | 2017-06-10 | 2018-01 to 2019-09, 2026-06 to 2026-07 | BLR (after 2021-11-28), RUS (after 2022-02-28) |
| Events | 2016-08-28 | none | BLR (after 2021-11-28), RUS (after 2022-02-28) |

Bookmakers: an FT 1X2 closing price, counted on the competition-seasons for which the bookmaker was collected. A
gap is a calendar month (with at least 30 matches) in which fewer than half of the matches have it. The same table is in the README,
and the [Verify before you buy notebook](https://www.kaggle.com/code/oliviersportsdata/world-football-odds-verify-before-you-buy) recomputes it from the files.

---

## Said plainly

Stated up front rather than discovered after paying.

- **Coverage differs by competition and over time.** The README gives it competition by competition and season by
  season, and its chapter for each pack lists every gap and every correction.
- **Some books were not collected for a few competitions** (Belarus, Russia, Moldova, North Macedonia; EURO 2020,
  the 2018 and 2022 World Cups; parts of Argentina and the USA): empty, never filled from another book.
- **Lineups depend on the league.** Share of matches with both starting elevens, per pack: Big 6 Europe 98 %, Other European Leagues 55 %, International 85 %, Americas 79 %, Asia & Africa 48 %.
- **`Kickoff_UTC` is the scheduled kickoff.** The closing price is the last quote before it: never an in-play price.
- **Score and clock on in-play quotes are the bookmaker's own:** Pinnacle almost never sends a numeric clock, Betfair
  often a partial score; nothing is filled in from another book.
- **Minute-by-minute statistics have no recording time before 2021-05-10:** `Minute` and `Value` are always there.
- **A closing quote is the last pre-match price recorded.** Median gap to kickoff on FT 1X2: Pinnacle 4 min, Betfair 6 min, Betsson 10 min, Bet365 25 min, Unibet 1.8 h.
- **The other bookmakers' table is a dated snapshot, not a closing price:** check `Minutes_Before_Kickoff`.
- **Some matches are missing from the source** (first matchdays of 2016, seasons stopped by COVID, results decided
  by a federation): each pack chapter of `sample/README.md` lists them, and every source event removed, with its reason.
- **Data starts on 2016-08-28.** The current seasons stop at 2026-09-30.
- **Odds are UTC and come from one provider.** No cross-provider reconciliation is claimed.

---

## What in-play looks like, in this sample

PSG 1-1 Arsenal, Champions League final, Budapest, 30 May 2026. Arsenal scored early, PSG
equalised in the second half, extra time stayed 1-1 and PSG won the shoot-out 4-3. Bet365 full-time 1X2
(the 90-minute market), in-play, around each goal. Every row is in `sample/odds_timestamped/Ultimate_Odds_Timestamped_UEFA_CL.csv.gz`.

| Timestamp (UTC) | Min | Score | PSG | Draw | Arsenal |
|---|---:|---|---:|---:|---:|
| 2026-05-30T16:02:40Z |  | 0-0 | 2.4 | 3.25 | 2.9 |
| 2026-05-30T16:07:06Z | 5 | 0-0 | suspended | | |
| 2026-05-30T16:07:08Z | 5 | 0-1 | 4.75 | 3.4 | 1.8 |
| 2026-05-30T17:29:11Z | 64 | 0-1 | 7.5 | 3.5 | 1.571 |
| 2026-05-30T17:29:33Z | 64 | 1-1 | 3.2 | 1.909 | 4.5 |

Quotes are never smoothed: a suspended market is an empty price with `Suspended` = 1, and clocks are delivered as
the bookmaker sent them.

168 in-play Bet365 1X2 quotes on this match alone, 3,207 quotes from
the 5 books in all, and the lineups, the events (the shoot-out kick by kick), the team statistics and the
minute-by-minute statistics of the same match in the other tables.

```python
import pandas as pd

o = pd.read_csv("sample/odds_timestamped/Ultimate_Odds_Timestamped_UEFA_CL.csv.gz", dtype={"Match_ID": str})
live = o[(o.Match_ID == "11854567") & (o.Book == "Bet365") &
         (o.Market == "FT_1X2") & (o.Phase == "In-play")]
print(live[["Timestamp_UTC", "Minute", "Score_Home", "Score_Away",
            "Price_Home", "Price_Draw", "Price_Away", "Suspended"]].to_string())
```

---

## Eight tables, one key

Everything joins on `Match_ID`. No fuzzy name matching.

| File | One row per | Key content |
|---|---|---|
| `Ultimate_Matches.csv` / `.xlsx` | match | competition, season, stage, matchday, leg, kickoff, scores HT / 90' / AET / penalties, aggregate, table positions, formations, managers, referee, venue, neutral-venue flag |
| `Ultimate_Opening_Closing_Odds.csv` / `.xlsx` | match | open and close per book and market, each with its time |
| `odds_timestamped/` (one `.csv.gz` per competition) | price update | book, market, phase, prices, line, score, clock, suspension, UTC, epoch |
| `bookmaker_snapshots/` (one `.csv.gz` per competition) | snapshot | 37 more books: first and last pre-match snapshot, with minutes before kickoff |
| `Ultimate_Team_Stats.csv` / `.xlsx` | match × team | 29 metrics incl. xG |
| `lineups/` (one `.csv.gz` per competition) | player × match | starters, subs, shirt, position |
| `events/` (one `.csv.gz` per competition) | event | 13 event types with minute and player |
| `minute_stats/` (one `.csv.gz` per competition) | stat × minute | running stats minute by minute |

Plus `Ultimate_Coverage.csv` / `.xlsx`: one row per competition and season, coverage of every table and book in %.

The complete column dictionary, the coverage tables and one chapter per pack (seasons and stages, knockout rules,
integrity notes, known limitations) are in `sample/README.md`, the README shipped with the product.

**Nothing a spreadsheet can reinterpret.** Scores, minutes and shoot-outs are separate integer
columns. Timestamps are full ISO 8601 with the T and the Z, plus an epoch. Formations are digits
(4231 = 4-2-3-1), so 4-4-2 never becomes 4 April 2002. Seasons read 2016/17 or 2019. Every cell
was audited against Excel auto-conversion patterns at write time: zero risky cells. A closing price
is never an in-play price.

---

## Licence

Sample: free to explore and evaluate.
Full product: single commercial user. Research, modelling and internal use permitted.
Redistribution and resale of the files are not.

A question before buying: contact@oliviersportsdata.com

---

👉 ⚽ **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/ylkgqx?utm_source=github&utm_medium=repo&utm_campaign=all_in_one_premium&utm_content=readme_bottom)** 👈

---

*Olivier Sports Data — From Chicken Area 🐔*
Hand-built historical sports market data.
[README.md](https://github.com/user-attachments/files/33925999/README.md)
