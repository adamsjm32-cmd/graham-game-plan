# Graham's Game Plan

Graham's two-week school game plan: calendar, science study packet, Fish in a Tree coach and essay coach.

Live page: https://adamsjm32-cmd.github.io/graham-game-plan/

## Reps: spelling + math facts (`spelling/`)

Graham's practice game, one app with a Spelling / Math switch: https://adamsjm32-cmd.github.io/graham-game-plan/spelling/

- **Math Reps:** Multiplication (2s-12s, 66 facts), Division (66 fact families) and Fraction · Decimal · % benchmarks (14 facts). Each deck starts with a Speed Check, then 20-rep practices that mix up to 3 training facts (each shown 3 times) with known facts. Mastered = right and fast on 3 different days. Each fact earns at most $0.25 in total; nothing is lost.
- The URL stays `/spelling/` so existing Home Screen icons and sync links keep working.

- Works in Safari on iPhone (Share > Add to Home Screen) and in any browser on a computer.
- **Sync between devices:** one-time setup with `spelling/sync-Code.gs` as a Google Apps Script web app (steps in the Coach Room > Data > Sync). The save file lives in the parent's Google Drive as `spelling-reps-save.json`. The family key is never stored in this repo.
- Quality checks: `spelling/tests.html` (uses a separate test save).
