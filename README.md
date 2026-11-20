# 🏒 NHL Opening & Closing Odds — 9 US Books, Pinnacle, Kalshi & Polymarket (2020–2026)

**20 games — every season from the 2020 playoffs, six Stanley Cup Final games, the first prices of six sources**

Most NHL odds archives give you one closing number per game, from one book.

The full dataset puts **up to 13 sources side by side on each game, in American odds**: FanDuel, DraftKings, BetMGM,
Caesars, BetRivers, BetOnline, theScore, Fanatics and Hard Rock, with Pinnacle, Bet365, Kalshi and Polymarket.
Moneyline, puck line and total, plus Pinnacle's team totals: **the opening and the closing price, each with the time
it was recorded**.

→ **[Get the full archive](https://sportsdataolivier.gumroad.com/l/gkqmny?utm_source=github&utm_medium=readme&utm_campaign=nhl_us&utm_content=hero)** — 8,301 games, August 2020 to 31 October 2026 · also on [Whop](https://whop.com/oliviersportsdata/nhl-opening-closing-odds-9-us-books-pinnacle-2020-2026/?utm_source=github&utm_medium=readme&utm_campaign=nhl_us&utm_content=whop_hero)

This sample is cut from the full file: the same 288 columns, the rows copied byte for byte, at about 0.2% scale.

---

## One game, every source

Maple Leafs at Oilers, 24 October 2026, moneyline. All 13 sources opened and closed it, and every one of them closed
the Oilers longer than it opened them. Toronto won 7-2.

| Source | Open, Oilers / Maple Leafs | Close, Oilers / Maple Leafs |
|---|---|---|
| Pinnacle | -175 / +154 | -138 / +125 |
| Bet365 | -208 / +156 | -159 / +119 |
| FanDuel | -196 / +162 | -146 / +122 |
| DraftKings | -175 / +145 | -149 / +124 |
| BetMGM | -190 / +155 | -150 / +125 |
| Caesars | -182 / +152 | -150 / +127 |
| BetRivers | -182 / +155 | -157 / +130 |
| BetOnline | -180 / +158 | -141 / +124 |
| theScore | -185 / +155 | -140 / +120 |
| Fanatics | -180 / +150 | -145 / +120 |
| Hard Rock | -180 / +150 | -140 / +120 |
| Kalshi | -178 / +150 | -144 / +138 |
| Polymarket | -163 / +156 | -138 / +133 |

---

## What's in this sample

| | |
|---|---|
| Games | 20 — every season from the 2020 playoffs to 2026-27 |
| Stages | 11 regular season · 9 playoffs: 6 Stanley Cup Final games, 2 games of the 2020 bubble's qualifying round and round-robin, 1 first-round game |
| Endings | 17 in regulation, 2 in overtime, 1 in a shootout |
| Prices | 1,556 |
| Sources | 13 — Pinnacle, Bet365, FanDuel, DraftKings, BetMGM, Caesars, BetRivers, BetOnline, theScore, Fanatics, Hard Rock, Kalshi, Polymarket |
| Columns | 288 |
| File | `NHL_Opening_Closing_Odds_2020-2026_SAMPLE.csv`, plus the README of the full product |

| Date (ET) | Game | Stage | Final, away–home | Sources, closing / opening ML |
|---|---|---|---|---:|
| 1 Aug 2020 | Jets @ Flames | Playoffs | 1–4 | 5 / 3 |
| 3 Aug 2020 | Capitals @ Lightning | Playoffs | 2–3 SO | 4 / 3 |
| 28 Sep 2020 | Lightning @ Stars | Playoffs | 2–0 | 5 / 2 |
| 13 Jan 2021 | Penguins @ Flyers | Regular Season | 3–6 | 7 / 2 |
| 17 May 2021 | Bruins @ Capitals | Playoffs | 4–3 OT | 8 / 7 |
| 12 Oct 2021 | Kraken @ Golden Knights | Regular Season | 3–4 | 7 / 7 |
| 26 Jun 2022 | Avalanche @ Lightning | Playoffs | 2–1 | 5 / 1 |
| 2 Jan 2023 | Penguins @ Bruins | Regular Season | 1–2 | 7 / 7 |
| 13 Jun 2023 | Panthers @ Golden Knights | Playoffs | 3–9 | 7 / 2 |
| 14 Nov 2023 | Ducks @ Predators | Regular Season | 3–2 | 9 / 8 |
| 16 Jan 2024 | Coyotes @ Flames | Regular Season | 2–3 OT | 1 / 1 |
| 24 Jun 2024 | Oilers @ Panthers | Playoffs | 1–2 | 8 / 2 |
| 8 Oct 2024 | Blackhawks @ Utah HC | Regular Season | 2–5 | 7 / 2 |
| 14 Mar 2025 | Red Wings @ Hurricanes | Regular Season | 2–4 | 10 / 6 |
| 17 Jun 2025 | Oilers @ Panthers | Playoffs | 1–5 | 10 / 2 |
| 7 Oct 2025 | Blackhawks @ Panthers | Regular Season | 2–3 | 11 / 2 |
| 17 Dec 2025 | Kings @ Panthers | Regular Season | 2–3 | 11 / 9 |
| 14 Jun 2026 | Hurricanes @ Golden Knights | Playoffs | 3–0 | 12 / 1 |
| 24 Oct 2026 | Maple Leafs @ Oilers | Regular Season | 7–2 | 13 / 13 |
| 31 Oct 2026 | Maple Leafs @ Canucks | Regular Season | 4–2 | 13 / 13 |

*Sources* counts, out of 13, the sources with a closing / opening moneyline for that game. Why each game is
here, game by game: `sample/README.md`.

---

## In this repository

| File | Content |
|---|---|
| `sample/NHL_Opening_Closing_Odds_2020-2026_SAMPLE.csv` | the 20 games, 288 columns |
| `sample/README.md` | why each game is here, then the README of the full product |
| `NHL_US_Verify_Before_You_Buy.ipynb` | the figures of the listing and of its README recomputed from the full file (all the file can show), results shown |

---

## Columns

| Block | Columns | Content |
|---|---:|---|
| Game | 18 | `League`, `Game_ID` (`YYYYMMDD_AWAY_HOME`, US Eastern date), `NHL_Game_ID`, `Season`, `Stage`, `Kickoff_UTC`, `Epoch`, teams, final score, `Winner`, `Total_Score`, `Margin`, `Match_Ending`, score after 60 minutes, `Result_60` |
| Pinnacle | 38 | moneyline, puck line and total, opening then closing, with the time of each, plus the team totals of both teams |
| Bet365 and the 9 US books | 22 each | moneyline, puck line and total, opening then closing, with the time of each |
| Kalshi, Polymarket | 6 each | moneyline only |

`{Book}_ML_Home_Open` · `{Book}_ML_Home_Close` · `{Book}_ML_Close_Time` · `{Book}_PuckLine_Home_Line_Close` · `{Book}_Total_Line_Close` · `Pinnacle_Team_Total_Home_Line_Close` — the prefixes are `Pinnacle_`, `Bet365_`, `FanDuel_`, `DraftKings_`, `BetMGM_`, `Caesars_`, `BetRivers_`, `BetOnline_`, `theScore_`, `Fanatics_`, `HardRock_`, `Kalshi_`, `Polymarket_`.

### How to read it

**Prices are American odds**, as integers: `-150`, and `130` for +130. **The puck line is ±1.5 only, the home team's line:** `-1.5` means the home team gives 1.5 goals. **Moneyline, puck line, total and team totals include overtime and the shootout**, as US books settle them; `Home_Score_60`, `Away_Score_60` and `Result_60` give the score after 60 minutes. **Times are UTC**, ISO 8601 with the T and the Z. **The opening price is the first price recorded for the game, the closing price the last pre-game one**; each one carries its own time, so you can see how close to the start it was taken.

```python
import pandas as pd

df = pd.read_csv("NHL_Opening_Closing_Odds_2020-2026_SAMPLE.csv")

def prob(us):  # American odds -> implied probability
    return (-us / (-us + 100)).where(us < 0, 100 / (us + 100))

# Pinnacle's no-vig probability of the home team at the close
h, a = prob(df["Pinnacle_ML_Home_Close"]), prob(df["Pinnacle_ML_Away_Close"])
pinnacle_home = h / (h + a)

# how far four US books moved the total, open to close
books = ["FanDuel", "DraftKings", "BetMGM", "Caesars"]
total_move = pd.DataFrame({b: df[b + "_Total_Line_Close"] - df[b + "_Total_Line_Open"] for b in books})

# how close to the start Bet365's closing moneyline was recorded, in minutes
start = pd.to_datetime(df["Kickoff_UTC"])
bet365_close_min = (pd.to_datetime(df["Bet365_ML_Close_Time"]) - start).dt.total_seconds() / 60
```

---

## Said plainly

- **The file starts on 1 August 2020, with the 2020 playoffs**: the US books' NHL prices start there.
- **Moneyline, puck line, total and team totals include overtime and the shootout**, as US books settle them. The score after 60 minutes is in its own columns.
- **Arizona Coyotes, 311 games (August 2020 to April 2024): the US books have no moneyline and no puck line on them.** Bet365 has the moneyline on 302 and the puck line on 309, and the US books' totals are there.
- **Pinnacle has no moneyline for 462 games**: the Arizona games, the 82 Utah Hockey Club games of 2024-25, 58 games of the 2020 playoffs and 11 others. BetOnline has no price on the Arizona and Utah Hockey Club games.
- **Bet365's moneyline is recorded when it changes**: its closing time is a median 76 minutes before the scheduled start. Its puck line and total close at the start.
- **BetRivers has no two-way moneyline before 17 May 2021**, and its prices before 2026-27 come from market snapshots.
- **theScore starts on 14 November 2023, Hard Rock on 14 March 2025, Fanatics on 7 October 2025**: closing prices only before 2026-27 for Hard Rock and Fanatics. Fanatics is on 11 games of 2025-26, then on every game of 2026-27 to 31 October 2026.
- **Kalshi and Polymarket: moneyline only**, closing prices from 17 December 2025 and 5 January 2026, opening prices from 21 October 2026. From the start of 2026-27 to 31 October 2026, their closing prices are identical in 125 of the 219 games where both have one.
- **Team totals come from Pinnacle only**, 13 January 2021 to 14 June 2026; none in 2026-27 to 31 October 2026.
- **No preseason, no All-Star games, no player props, no periods, no live odds, no futures.** One opening and one closing price per book and market, not every move in between. Every recorded move (timestamped odds), other books or another scope: built to order on request.

---

## Verify before you buy

The figures of the listing and of its README — games, prices, the sources and their first price, coverage, opening
and closing times, the gaps stated above, the games on the listing's images — recomputed from the full file and
printed PASS or FAIL, all but what the file cannot show (the counts of prices left out while it was built):
[on Kaggle](https://www.kaggle.com/code/oliviersportsdata/nhl-us-books-odds-verify-before-you-buy) · [on GitHub](https://github.com/ovignez-hash/nhl-opening-closing-odds-us-books-pinnacle/blob/main/NHL_US_Verify_Before_You_Buy.ipynb) (results shown).

---

## The full dataset

| | Sample | Full |
|---|---|---|
| Games | 20 | 8,301 |
| Seasons | 2020 playoffs to 2026-27 | 2020 playoffs to 2026-27, through 31 Oct 2026 |
| Prices | 1,556 | 810,920 |
| Columns | 288 | 288 |
| Files | 1 CSV + README | 1 CSV + README |

Once a year, after the Stanley Cup Final, the file adds the completed season. The games after 31 October 2026 come with
the [NHL US books monthly updates](https://sportsdataolivier.gumroad.com/l/yqlcwk?utm_source=github&utm_medium=readme&utm_campaign=nhl_us&utm_content=monthly): each month's games, same 288 columns, ready to append.

→ **[Get the full archive](https://sportsdataolivier.gumroad.com/l/gkqmny?utm_source=github&utm_medium=readme&utm_campaign=nhl_us&utm_content=footer)** · also on [Whop](https://whop.com/oliviersportsdata/nhl-opening-closing-odds-9-us-books-pinnacle-2020-2026/?utm_source=github&utm_medium=readme&utm_campaign=nhl_us&utm_content=whop_footer)

---

## Licence

Sample: free to explore and evaluate.
Full product: single commercial user. Use the data as you wish, including the models, predictions and products you sell.
Redistribution and resale of the files, or of the raw data in another format, are not permitted.

A question, an invoice or a custom extract: contact@oliviersportsdata.com

---

*Olivier Sports Data — From Chicken Area 🐔*
