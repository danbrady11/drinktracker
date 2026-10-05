# drinktracker

A simple year-at-a-glance drink tracker. Each day of the year is a square, colored by how much you drank:

| Color | Meaning |
|---|---|
| Green | No drinks |
| Yellow | 1–2 drinks |
| Orange | 3–5 drinks |
| Red | 6+ drinks |
| Dark gray | Blackout |

Tap **Log today**, a day in the "Last 7 days" row, a calendar square, or 📅 to pick any past date. Then add each beer or whiskey with its size (oz) and ABV. The app converts them to US standard drinks (0.6 oz of pure alcohol) and colors the day by the total. Tap a logged drink to change its size or ABV, or ✕ to remove it. You can also mark a day as dry or as a blackout. Data is stored in your browser (`localStorage`) on that device — use **Export backup** occasionally so you don't lose it if you clear Safari/Chrome data.

## Hosting on GitHub Pages

1. Repo **Settings → Pages**.
2. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Open `https://<your-username>.github.io/drinktracker/` on your phone and bookmark it (or Share → **Add to Home Screen** for an app-style icon).
