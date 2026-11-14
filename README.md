# Hive Scout

A simple match-scouting app for the FTC 2026–27 game **BioBuzz**.

- Enter your team number to find your competition. The live match schedule comes from the [FTCScout API](https://ftcscout.org/api).
- Tap a team in a match to scout it: count **Auto** and **TeleOp hive tips**, tap the tiles the robot **shot from** on a top-down BioBuzz field (official A1–F6 tile names), and flag **NECTAR jammed in intake**, **easily pushed around**, or **disconnected (DC)**.
- **Live scoring:** hit **GO** (Enter) when the match starts. A 30s Auto → 8s transition → 2:00 TeleOp clock runs, and you log what happens as it happens: Space = hive tip, X = missed shot, J = nectar jam, P = pushed, D = disconnected/back online, Z = undo, arrow keys or tap = robot position. On a phone, tap the buttons.
- **After-match survey:** driver skill, cycle speed, defense, "would you pick them?", and notes. You can remove mistakes from the match log before saving.
- **Demo:** "Try the demo" on the first screen loads a made-up schedule so you can try a full match.
- The **Teams** tab ranks teams by average hive tips, shows a heat map of their shooting tiles, and counts jams, pushes and DCs.

Data is saved on each phone. To combine scouts' data, each scout taps **Copy data** on the Teams tab and sends it to the lead scout, who pastes it into **Import**.

Tip: open the site on your phone and choose **Add to Home Screen** so it works like an app.
