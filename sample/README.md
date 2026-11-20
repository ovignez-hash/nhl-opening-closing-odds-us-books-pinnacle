# NHL Opening & Closing Odds, US Books — free sample, 20 games

**Free sample: 20 of the 8,301 games of the full product** (as of 31 October 2026). Same file layout, same 288
columns: every row is copied byte for byte from the full CSV. Only the number of games differs.

`NHL_Opening_Closing_Odds_2020-2026_SAMPLE.csv` — 20 rows, 288 columns, UTF-8, comma-separated. 1,556 prices.

🏒 **[→ The full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/gkqmny?utm_source=github&utm_medium=sample_readme&utm_campaign=nhl_us&utm_content=readme)**

## The 20 games

Every season from the 2020 playoffs to 2026-27: 11 regular season · 9 playoffs: 6 Stanley Cup Final games, 2 games of the 2020 bubble's qualifying round and round-robin, 1 first-round game. 2 went to overtime, 1 to a shootout.
*Closing ML* and *Opening ML* count the sources, out of 13, with a moneyline for that game.

| Date (ET) | Game | Stage | Final, away–home | Closing ML | Opening ML | Why it is here |
|---|---|---|---|---:|---:|---|
| 1 Aug 2020 | Winnipeg Jets @ Calgary Flames | Playoffs | 1–4 | 5 | 3 | The first day of the file, a qualifying-round game played in the Edmonton bubble: Pinnacle's first moneyline and puck line. |
| 3 Aug 2020 | Washington Capitals @ Tampa Bay Lightning | Playoffs | 2–3 SO | 4 | 3 | Round-robin game of the Toronto bubble, played under regular-season overtime rules: one of the two playoff games of the file decided in a shootout. |
| 28 Sep 2020 | Tampa Bay Lightning @ Dallas Stars | Playoffs | 2–0 | 5 | 2 | Stanley Cup Final, Game 6: Tampa Bay wins the Cup. Pinnacle has no moneyline on this game. |
| 13 Jan 2021 | Pittsburgh Penguins @ Philadelphia Flyers | Regular Season | 3–6 | 7 | 2 | Opening night of the 56-game 2020-21 season: Pinnacle's team totals start. |
| 17 May 2021 | Boston Bruins @ Washington Capitals | Playoffs | 4–3 OT | 8 | 7 | Playoffs, first round, Game 2, overtime: BetRivers' first two-way moneyline. |
| 12 Oct 2021 | Seattle Kraken @ Vegas Golden Knights | Regular Season | 3–4 | 7 | 7 | The Seattle Kraken's first game. |
| 26 Jun 2022 | Colorado Avalanche @ Tampa Bay Lightning | Playoffs | 2–1 | 5 | 1 | Stanley Cup Final, Game 6: Colorado wins the Cup. |
| 2 Jan 2023 | Pittsburgh Penguins @ Boston Bruins | Regular Season | 1–2 | 7 | 7 | The Winter Classic at Fenway Park. |
| 13 Jun 2023 | Florida Panthers @ Vegas Golden Knights | Playoffs | 3–9 | 7 | 2 | Stanley Cup Final, Game 5: Vegas wins the Cup. |
| 14 Nov 2023 | Anaheim Ducks @ Nashville Predators | Regular Season | 3–2 | 9 | 8 | theScore's first price. |
| 16 Jan 2024 | Arizona Coyotes @ Calgary Flames | Regular Season | 2–3 OT | 1 | 1 | An Arizona Coyotes game, overtime: on Arizona's games the US books have no moneyline or puck line. Bet365's are here, with Pinnacle's opening puck line and total and the US books' totals. |
| 24 Jun 2024 | Edmonton Oilers @ Florida Panthers | Playoffs | 1–2 | 8 | 2 | Stanley Cup Final, Game 7: Florida wins the Cup. |
| 8 Oct 2024 | Chicago Blackhawks @ Utah Hockey Club | Regular Season | 2–5 | 7 | 2 | The Utah Hockey Club's first game. On Utah's 2024-25 games, Pinnacle has no moneyline (here, its opening puck line and total) and BetOnline no price; the other US books are here. |
| 14 Mar 2025 | Detroit Red Wings @ Carolina Hurricanes | Regular Season | 2–4 | 10 | 6 | Hard Rock's first price. |
| 17 Jun 2025 | Edmonton Oilers @ Florida Panthers | Playoffs | 1–5 | 10 | 2 | Stanley Cup Final, Game 6: Florida wins the Cup again. |
| 7 Oct 2025 | Chicago Blackhawks @ Florida Panthers | Regular Season | 2–3 | 11 | 2 | Opening night of 2025-26: Fanatics' first price. |
| 17 Dec 2025 | Los Angeles Kings @ Florida Panthers | Regular Season | 2–3 | 11 | 9 | Kalshi's first price. Polymarket follows on 5 January 2026. |
| 14 Jun 2026 | Carolina Hurricanes @ Vegas Golden Knights | Playoffs | 3–0 | 12 | 1 | Stanley Cup Final, Game 6: Carolina wins the Cup. 12 of the 13 sources close the moneyline. |
| 24 Oct 2026 | Toronto Maple Leafs @ Edmonton Oilers | Regular Season | 7–2 | 13 | 13 | All 13 sources open and close the moneyline, and every one of them closed the Oilers longer than it opened them. Toronto won 7-2. |
| 31 Oct 2026 | Toronto Maple Leafs @ Vancouver Canucks | Regular Season | 4–2 | 13 | 13 | The last day of the file: all 13 sources open and close the moneyline. |

---

*Below: the README of the full product, as shipped in its ZIP.*

# NHL Opening & Closing Odds — 11 books and 2 prediction markets, 2020–2026

One row per game. 8,301 NHL games from 1 August 2020 to 31 October 2026: the 130 playoff games of 2019-20 played in August and September 2020, then seasons 2020-21 through 2026-27, the 2026-27 season through 31 October (226 games). Regular season and playoffs. No preseason, no All-Star games.

For every book and every market, the opening price and the closing price where the sources have them, each with the time it was recorded. Pinnacle adds the team totals of both teams from 2020-21 to 2025-26.

| | |
|---|---|
| Games | 8,301 |
| Seasons | 2019-20 (playoffs) to 2026-27 |
| Books | Pinnacle · Bet365 · FanDuel · DraftKings · BetMGM · Caesars · BetRivers · BetOnline · theScore · Fanatics · Hard Rock |
| Prediction markets | Kalshi · Polymarket (moneyline only) |
| Markets | Moneyline · Puck line ±1.5 · Total · Team totals (Pinnacle) |
| Prices | 810,920 |
| Columns | 288 |
| File | `NHL_Opening_Closing_Odds_2020-2026.csv` (UTF-8, comma-separated) |

## Games

| Season | Regular season | Playoffs | Total |
|---|---:|---:|---:|
| 2019/2020 | – | 130 | 130 |
| 2020/2021 | 868 | 84 | 952 |
| 2021/2022 | 1,312 | 89 | 1,401 |
| 2022/2023 | 1,312 | 88 | 1,400 |
| 2023/2024 | 1,312 | 88 | 1,400 |
| 2024/2025 | 1,312 | 86 | 1,398 |
| 2025/2026 | 1,312 | 82 | 1,394 |
| 2026/2027 | 226 | – | 226 |

The game list, the scores, the way each game ended and the scheduled start times follow the NHL's official record, game by game. 2019/2020 is here for its playoffs only, played in Edmonton and Toronto from 1 August 2020: the qualifying round and the seeding round-robin, which the NHL counts as playoff games, then the four rounds. Two of the round-robin games (Washington at Tampa Bay on 3 August 2020, Dallas at St. Louis on 9 August 2020) ended in a shootout, the only two playoff games that did. 2020/2021 was a 56-game season. Seattle joined in 2021-22. 1,299 games were decided in overtime and 558 in a shootout.

## Columns

**Game — 18 columns**

| Column | Content |
|---|---|
| `League` | NHL |
| `Game_ID` | `YYYYMMDD_AWAY_HOME`, date in US Eastern time, team codes of the time |
| `NHL_Game_ID` | the NHL's own game number (`2020020001`: season, game type, game), to join with official game data |
| `Season` | `2020/2021` |
| `Stage` | `Regular Season` or `Playoffs` |
| `Kickoff_UTC` | scheduled start, ISO 8601 (`2021-01-13T22:30:00Z`) |
| `Epoch` | the same instant in Unix seconds |
| `Home_Team`, `Away_Team` | full team names, as the team was named that season |
| `Home_Score`, `Away_Score` | official final score: overtime included, and a shootout counts as one goal for the winner |
| `Winner` | `Home` or `Away` |
| `Total_Score` | home plus away goals, final score |
| `Margin` | absolute difference between the two scores, never negative |
| `Match_Ending` | `Regulation`, `Overtime` or `Shootout` |
| `Home_Score_60`, `Away_Score_60` | score after 60 minutes (regular time). A game decided in overtime or a shootout was tied after 60 minutes, at the loser's final score |
| `Result_60` | `Home`, `Draw` or `Away` after 60 minutes |

Team names follow the season: Arizona Coyotes (`ARI`) until 2023-24; Utah Hockey Club in 2024-25, then Utah Mammoth (`UTA` for both); Seattle Kraken (`SEA`) from 2021-22.

**Odds — 22 columns per book**, opening first, then closing:

```
{Book}_ML_Home_Open               {Book}_ML_Home_Close
{Book}_ML_Away_Open               {Book}_ML_Away_Close
{Book}_ML_Open_Time               {Book}_ML_Close_Time
{Book}_PuckLine_Home_Line_Open    ... _Close
{Book}_PuckLine_Home_Open         ... _Close
{Book}_PuckLine_Away_Open         ... _Close
{Book}_PuckLine_Open_Time         ... _Close_Time
{Book}_Total_Line_Open            ... _Close
{Book}_Total_Over_Open            ... _Close
{Book}_Total_Under_Open           ... _Close
{Book}_Total_Open_Time            ... _Close_Time
```

Kalshi and Polymarket carry the moneyline columns only, 6 each. Hard Rock's columns start with `HardRock_`.

**Team totals — 16 more columns for Pinnacle**, one over/under per team, placed after Pinnacle's total columns (opening, then closing):

```
Pinnacle_Team_Total_Home_Line_Open    ... _Close
Pinnacle_Team_Total_Home_Over_Open    ... _Close
Pinnacle_Team_Total_Home_Under_Open   ... _Close
Pinnacle_Team_Total_Home_Open_Time    ... _Close_Time
```

The same four with `Away` for the away team.

### How to read it

**Prices are American odds**, as integers: `-150`, and `130` for +130. Even money is written `100`.

**Moneyline, total and team totals include overtime and the shootout**, as US books settle them: the winner's shootout goal counts as one goal, as in the final score. On the lines where overtime changes the result (4.5, 6.5, 8.5), every book's closing total matches the final score, not the score after 60 minutes.

**The puck line is ±1.5 only, and it is the home team's line.** `-1.5` means the home team gives 1.5 goals; the away team's line is the opposite. Each book's puck line is its standard one, with the favourite at -1.5: of the two ±1.5 pairs, the more balanced one.

**The total line is in goals**, the same for over and under.

**A team total is the goals of one team.** `Pinnacle_Team_Total_Home_Line_Close` at `3.5` is over or under 3.5 goals for the home team.

**Kalshi and Polymarket are prediction markets.** Their prices are written as American odds. When the source gives no American price, the price is the cost of buying each side (the ask), converted to American odds.

**One time per book, market and phase.** The `_Time` columns are ISO 8601 in UTC and give the moment the price was recorded. Most closing prices of the US books are recorded at the same second for all of them, a few minutes before the start. Some closing prices come from snapshots of the market: all those of BetRivers, Fanatics and Hard Rock before 2026-27, and a minority of the other US books' (FanDuel 8%, DraftKings 5%, BetMGM 5%, Caesars 9%, theScore 3% of their prices). Their time is the book's last price update seen in the snapshot, which can be hours before the start when the book did not move. Bet365's moneyline is recorded when it changes, to the minute; its puck line and total are recorded at every change, to the second. The table counts, per season, the games where at least one moneyline, puck line or total closing price of the book is stamped more than 15 minutes before the scheduled start:

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 18 | 36 | 66 | 60 | 68 | 68 | 57 | 3 | – | – | – |
| 2020/2021 | 14 | 719 | 55 | 159 | 139 | 617 | 753 | 1 | – | – | – |
| 2021/2022 | 5 | 1,035 | 46 | 256 | 145 | 6 | 790 | 4 | – | – | – |
| 2022/2023 | 104 | 1,112 | 43 | 74 | 59 | 59 | 1,136 | 3 | – | – | – |
| 2023/2024 | 166 | 1,067 | 66 | 76 | 62 | 61 | 1,122 | 1 | 46 | – | – |
| 2024/2025 | 151 | 920 | 60 | 76 | 77 | 91 | 1,005 | 1 | 81 | – | 93 |
| 2025/2026 | 309 | 967 | 4 | 2 | 6 | 14 | 5 | 3 | 3 | 0 | 10 |
| 2026/2027 | 10 | 122 | 3 | 3 | 4 | 5 | 1 | 5 | 2 | 0 | 4 |

**The opening price is the first price recorded for the game.**

**The closing price is the last pre-game price.** `Kickoff_UTC` is the scheduled start; the puck drops a few minutes later and books take bets until then. Median closing time on the moneyline, against the scheduled start: Pinnacle 5 min after, Bet365 76 min before, FanDuel 9 min before, DraftKings 9 min before, BetMGM 9 min before, Caesars 9 min before, BetRivers 36 min before, BetOnline 9 min before, theScore 9 min before, Fanatics at the start, Hard Rock 1 min after, Kalshi 1 min after, Polymarket at the start. No closing price is older than 12 hours before the scheduled start, and none is stamped more than 30 minutes after it.

**Closing prices were checked against the market at the start.** A closing price was compared with the median of the other books' closing prices recorded in the hour before the start on the same game, and left out when it was more than 0.05 away in no-vig implied probability on the moneyline, more than 0.10 on the same puck line, or 1 goal or more away on the total. When a book's first source failed that check and its other source passed it, the other source was used, opening price included (20 markets); otherwise the closing price was left out (169 prices).

## Coverage

Share of games with the price, in %, rounded down (`–` means none, `0` means less than 1%, 100 means every game).

**Closing moneyline**

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock | Kalshi | Polymarket |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 33 | 99 | 91 | 82 | 48 | 91 | – | 79 | – | – | – | – | – |
| 2020/2021 | 93 | 97 | 93 | 93 | 89 | 93 | 3 | 90 | – | – | – | – | – |
| 2021/2022 | 94 | 95 | 94 | 94 | 93 | 94 | 33 | 93 | – | – | – | – | – |
| 2022/2023 | 93 | 90 | 93 | 94 | 93 | 94 | 77 | 93 | – | – | – | – | – |
| 2023/2024 | 92 | 90 | 94 | 93 | 93 | 94 | 72 | 92 | 78 | – | – | – | – |
| 2024/2025 | 93 | 94 | 100 | 99 | 99 | 96 | 87 | 93 | 99 | – | 24 | – | – |
| 2025/2026 | 94 | 85 | 99 | 100 | 100 | 100 | 92 | 98 | 100 | 0 | 97 | 54 | 52 |
| 2026/2027 | 98 | 99 | 100 | 100 | 100 | 100 | 100 | 97 | 100 | 100 | 100 | 96 | 100 |

**Opening moneyline**

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock | Kalshi | Polymarket |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 37 | 81 | 72 | 73 | 32 | 82 | – | 70 | – | – | – | – | – |
| 2020/2021 | 93 | 84 | 87 | 89 | 86 | 88 | – | 88 | – | – | – | – | – |
| 2021/2022 | 94 | 84 | 76 | 92 | 91 | 89 | 13 | 85 | – | – | – | – | – |
| 2022/2023 | 94 | 83 | 91 | 92 | 91 | 91 | 31 | 86 | – | – | – | – | – |
| 2023/2024 | 94 | 78 | 92 | 92 | 91 | 90 | 82 | 87 | 68 | – | – | – | – |
| 2024/2025 | 93 | 64 | 92 | 92 | 91 | 86 | 81 | 88 | 85 | – | – | – | – |
| 2025/2026 | 99 | 84 | 97 | 98 | 95 | 97 | 64 | 95 | 94 | – | – | – | – |
| 2026/2027 | 100 | 94 | 97 | 97 | 97 | 89 | 88 | 100 | 96 | 48 | 92 | 21 | 33 |

**Closing puck line**

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 41 | 97 | 68 | – | 33 | 55 | 4 | 79 | – | – | – |
| 2020/2021 | 91 | 99 | 75 | 84 | 84 | 89 | 72 | 91 | – | – | – |
| 2021/2022 | 93 | 99 | 91 | 51 | 90 | 94 | 61 | 93 | – | – | – |
| 2022/2023 | 92 | 99 | 91 | 93 | 90 | 94 | 79 | 93 | – | – | – |
| 2023/2024 | 92 | 99 | 94 | 93 | 92 | 93 | 73 | 92 | 75 | – | – |
| 2024/2025 | 92 | 99 | 100 | 99 | 98 | 96 | 84 | 93 | 98 | – | 23 |
| 2025/2026 | 94 | 97 | 99 | 100 | 99 | 100 | 98 | 98 | 99 | 0 | 99 |
| 2026/2027 | 100 | 90 | 100 | 100 | 100 | 99 | 100 | 97 | 99 | 99 | 100 |

**Closing total**

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 63 | 96 | 57 | 53 | 2 | 56 | 50 | 79 | – | – | – |
| 2020/2021 | 93 | 99 | 98 | 88 | 82 | 91 | 74 | 93 | – | – | – |
| 2021/2022 | 93 | 99 | 97 | 99 | 96 | 44 | 64 | 93 | – | – | – |
| 2022/2023 | 93 | 99 | 97 | 99 | 97 | 98 | 80 | 93 | – | – | – |
| 2023/2024 | 92 | 99 | 100 | 99 | 97 | 98 | 69 | 92 | 81 | – | – |
| 2024/2025 | 93 | 99 | 99 | 99 | 98 | 95 | 79 | 93 | 99 | – | 23 |
| 2025/2026 | 92 | 97 | 99 | 99 | 99 | 99 | 97 | 98 | 100 | 0 | 97 |
| 2026/2027 | 100 | 93 | 99 | 100 | 100 | 100 | 95 | 98 | 100 | 99 | 99 |

**Opening puck line**

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 46 | 98 | 0 | – | 16 | 2 | – | 70 | – | – | – |
| 2020/2021 | 93 | 99 | 78 | 69 | 80 | 28 | 0 | 87 | – | – | – |
| 2021/2022 | 94 | 99 | 75 | 42 | 88 | 89 | 3 | 83 | – | – | – |
| 2022/2023 | 93 | 99 | 50 | 91 | 89 | 91 | 7 | 77 | – | – | – |
| 2023/2024 | 97 | 99 | 92 | 92 | 90 | 89 | 4 | 83 | 66 | – | – |
| 2024/2025 | 98 | 99 | 95 | 95 | 91 | 86 | 1 | 84 | 83 | – | – |
| 2025/2026 | 99 | 99 | 98 | 98 | 96 | 97 | 0 | 91 | 94 | – | – |
| 2026/2027 | 100 | 95 | 97 | 97 | 96 | 73 | 88 | 100 | 96 | 48 | 92 |

**Opening total**

| Season | Pinnacle | Bet365 | FanDuel | DraftKings | BetMGM | Caesars | BetRivers | BetOnline | theScore | Fanatics | Hard Rock |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 2019/2020 | 63 | 99 | 2 | 5 | 1 | 2 | 3 | 70 | – | – | – |
| 2020/2021 | 96 | 99 | 80 | 73 | 77 | 31 | 2 | 88 | – | – | – |
| 2021/2022 | 98 | 99 | 76 | 95 | 91 | 43 | 2 | 85 | – | – | – |
| 2022/2023 | 98 | 100 | 93 | 95 | 91 | 92 | 7 | 86 | – | – | – |
| 2023/2024 | 98 | 99 | 95 | 95 | 92 | 90 | 4 | 87 | 69 | – | – |
| 2024/2025 | 98 | 100 | 95 | 95 | 91 | 87 | 1 | 88 | 85 | – | – |
| 2025/2026 | 99 | 99 | 97 | 98 | 90 | 97 | 0 | 95 | 94 | – | – |
| 2026/2027 | 100 | 98 | 97 | 97 | 97 | 90 | 88 | 100 | 94 | 48 | 89 |

**Pinnacle team totals**

| Season | Home, opening | Away, opening | Home, closing | Away, closing |
|---|---:|---:|---:|---:|
| 2020/2021 | 93 | 93 | 93 | 93 |
| 2021/2022 | 94 | 94 | 94 | 94 |
| 2022/2023 | 94 | 94 | 93 | 93 |
| 2023/2024 | 94 | 94 | 92 | 92 |
| 2024/2025 | 93 | 93 | 92 | 92 |
| 2025/2026 | 99 | 99 | 93 | 93 |

## Said plainly

- **The file starts on 1 August 2020**, with the 2020 playoffs: the US books' NHL prices start there.
- **Pinnacle has no moneyline for 462 games**: all 311 Arizona Coyotes games (August 2020 to April 2024), all 82 Utah Hockey Club games of 2024-25, 58 games of the 2020 playoffs and 11 others. On these games Pinnacle has a total on 307 and a puck line on 137, mostly opening prices: 46 closing totals and 12 closing puck lines.
- **411 Pinnacle totals and puck lines come from a second timestamped record** (totals from February 2021, puck lines from 2023-24); 388 of them have an opening price only.
- **On the 311 Arizona Coyotes games, the US books have no moneyline and no puck line.** Bet365 has the moneyline on 302 of them and the puck line on 309, Pinnacle the puck line on 57; at least one US book has the total on 306.
- **BetOnline has no price on the Arizona games, nor on the 82 Utah Hockey Club games of 2024-25.** The other US books price most of Utah's games: moneyline at FanDuel 82, DraftKings 81, theScore 81, BetMGM 75, BetRivers 75, Caesars 55.
- **Bet365's moneyline is recorded when it changes**: its closing time is a median 76 minutes before the scheduled start, and the 12-hour limit leaves some games without one. Its puck line and total close at the start.
- **BetRivers' prices before 2026-27 come from market snapshots.** It has no two-way moneyline before 17 May 2021: the market recorded for it until then is the three-way regular-time one, which is not used. Its closing moneyline covers 33% of 2021-22, its opening moneyline starts on 30 December 2021, and it has almost no opening puck line or total before 2026-27.
- **theScore starts on 14 November 2023.**
- **Hard Rock starts on 14 March 2025 and Fanatics on 7 October 2025, closing prices only before 2026-27.** Fanatics is on 11 games of 2025-26, then on every game of 2026-27. Opening prices start on 29 September 2026 for Hard Rock and 3 October 2026 for Fanatics.
- **Kalshi carries closing prices from 17 December 2025 and Polymarket from 5 January 2026**, opening prices from 21 October 2026. In 2026-27, their closing prices are identical in 125 of the 219 games where both have one.
- **Team totals come from Pinnacle only**, from 13 January 2021 to 14 June 2026; 2026-27 has none yet.
- **When the opening record is the closing record itself (same moment), it appears once, as the closing price** (5,824 cases). An opening price equal to the closing price at a different time is kept: the book did not move. No opening price is stamped after the scheduled start. A book's opening and closing prices in a market always come from the same source. 3,162 markets have an opening price and no closing price.
- **Prices that contradict the market were removed rather than kept**: 76 puck lines giving -1.5 to the team the moneyline makes the underdog (no-vig probability below 0.42); 14 opening prices far from the other books' openings (more than 0.15 in no-vig implied probability on the moneyline, 0.20 on the puck line, 1.5 goals on the total) or from the market at the close. Prices that cannot exist were not used either: moneylines with less than 1.5% margin (the two sides were not taken at the same moment) or more than 25%, closing moneylines with more than 10% margin, puck line, total and team total prices adding up to less than 100% or more than 115%, total prices beyond ±250, prediction-market prices whose two sides do not add up, and lines out of range.
- **The 2020 playoffs were played on neutral ice.** Home and away follow the NHL's designation.
- **The 2026-27 season stops on 31 October 2026**, 226 games. Later months come with the monthly update.

## Quick start

```python
import pandas as pd

df = pd.read_csv("NHL_Opening_Closing_Odds_2020-2026.csv", low_memory=False)

# implied probability of the home team at Pinnacle's close
def prob(us):
    return -us / (-us + 100) if us < 0 else 100 / (us + 100)

p = df.Pinnacle_ML_Home_Close.dropna().map(prob)

# line movement: DraftKings total, open to close
move = df.DraftKings_Total_Line_Close - df.DraftKings_Total_Line_Open

# Pinnacle's two team totals against its game total, at the close
gap = (df.Pinnacle_Team_Total_Home_Line_Close + df.Pinnacle_Team_Total_Away_Line_Close
       - df.Pinnacle_Total_Line_Close)
```

*Olivier Sports Data — From Chicken Area 🐔*
