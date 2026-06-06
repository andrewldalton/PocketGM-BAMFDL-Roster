# PocketGM BAMFDL Roster

Custom Pocket GM roster for the BAMFDL dynasty league.

- **Veterans** re-rated to BAMFDL **Superflex ADV** (Andrew Dalton Value — composite of FantasyCalc, DynastyDaddy, RosterAudit, KTC, DraftSharks).
- **2026 rookie class** = the Rookie Radar consensus board (60 prospects), rated by mock ADP with real NFL draft slots.

## Import into Pocket GM
Paste this raw URL into Pocket GM's roster import:

```
https://raw.githubusercontent.com/andrewldalton/PocketGM-BAMFDL-Roster/main/Pre%20Draft%20ADV%20v6.0
```

Regenerated via `bamfdl-calc/pgm-export/build_adv_roster.py` + `build_rookie_class.py`.

## BAMFDL Owners (AFC) roster
The 12 BAMFDL managers as the 12 AFC East/North/West teams, each stocked with their live Sleeper roster (ADV-rated) plus kept defense/OL so every team is fieldable. Import URL:

```
https://raw.githubusercontent.com/andrewldalton/PocketGM-BAMFDL-Roster/main/BAMFDL%20Owners%20AFC%20v1
```

Owner → team: Andrew→KC · Austin→BUF · Nick→MIA · Matt→NE · Bsco→NYJ · Norman→BAL · Jalen→CIN · Jordan→CLE · Jesse→PIT · Ehran→DEN · Alex→LV · Westy→LAC

## Chiefs All-Time (proof of concept)
Kansas City's all-time 53 (Pro Football HOFers + Hall of Honor + modern stars), with a salary-cap solver: payroll distributed by a convex rating curve, capped at the league max, floored for depth, total ≈ $190M (cap-legal). Rest of the league is the real baseline. Import URL:

```
https://raw.githubusercontent.com/andrewldalton/PocketGM-BAMFDL-Roster/main/Chiefs%20All-Time
```
