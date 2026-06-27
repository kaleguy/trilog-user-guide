# Viewing Patterns

TriLog offers multiple ways to review your data. Each view shows different patterns.

## The Metrics Grid

Swipe right from the main chart to reach the Metrics view. This grid shows daily measurements in rows:

<img src="../images/metrics.png" alt="Metrics grid" width="350">

### What You See

Each row is a different metric:
- **Mood** — Colored bar showing your mood
- **Energy** — Numeric energy level
- **Sleep** — Hours of sleep
- **Steps** — Daily step count (if enabled)
- **Calories** — Daily calorie intake (if tracking meals)
- **Custom Trackers** — Any trackers you've created

Each column is a day of the week. You see seven days at once.

### Customizing the Grid

Tap the settings icon to choose which rows appear:

<img src="../images/metrics-visible-rows-modal.png" alt="Metrics visible rows" width="350">

Hide metrics you don't track. Show the ones you care about.

### Viewing Details

Tap any row header to see that metric in more detail—a focused view showing just that measurement over time.

---

## Analysis

Charts, auto-detected patterns, and deeper reports live in one place: **Menu → Analysis** (lines icon in the top-right, then **Analysis**). This replaced the old swipeable Charts and Ratings views.

<img src="../images/analysis/analysis.png" alt="Analysis launcher with Basic and Advanced reports" width="350">

The launcher lists reports as cards under **Basic** (free) and **Advanced** (Pro). Tap a card to open it; use the back arrow to return to the launcher.

### Patterns

Auto-detected findings from your mood and energy history — weekly rhythms, time-of-day energy dips, mood/energy coupling, and similar. Surfaces after you have enough data; cards explain each pattern in plain language.

<img src="../images/analysis/patterns.png" alt="Patterns report with auto-detected findings" width="350">

### Base Chart

Activity distribution and trends over time — stacked bar chart, mood/energy lines, and a **pie chart** showing how your hours actually divided across activities.

<img src="../images/analysis/base-pie-chart.png" alt="Base Chart pie view of activity breakdown" width="350">

Toggle between bar and pie modes. Switch between **7-day** and **21-day** windows (or navigate by week). Free.

### Day Ratings Chart

Your daily subjective ratings — Mood, Energy, Thrive, and a calculated **Energy Events** score — as two side-by-side line charts, each covering four weeks (28 days, Sunday to Saturday).

**Four toggles** (two rows at the bottom):

**Row 1:**
- **Mood** — Stacked vertical bars per day, proportional to your mood distribution (upset, anxious, sad, neutral, happy).
- **Thrive** — Your daily "on" rating (1–5) — how present or aligned you felt. Open green rings connected by a green line.

**Row 2:**
- **Day Energy** — The 1–5 energy rating from your daily summary. Colored dots connected by a gray line.
- **Energy Events** — A calculated weighted energy score combining individual energy entries with sleep activity throughout the day (sleep hours = 0; waking hours use last observation carried forward).

Tap a day for a tooltip with Energy, Thrive, and Energy Events. **View Notes** jumps to that day's notes.

<img src="../images/analysis/day-ratings-with-cycles.png" alt="Day Ratings Chart with Mood, Energy, Thrive, and Energy Events enabled" width="400">

Use the arrows at the top to move back and forward by four weeks.

### Day Ratings with Cycles

The same Day Ratings chart with your **menstrual cycle** overlaid as colored bands (requires cycle notes — log with `cy m` / `cy -m` prefixes or Menu → Extras → Cycles). Useful for spotting energy and mood shifts across your cycle.

<img src="../images/analysis/day-energy-vs-cycles.png" alt="Day Ratings with cycle bands and Day Energy only" width="400">

Toggle which ratings appear — e.g. show just **Day Energy** against cycle bands to isolate one signal.

### Advanced reports (Pro)

The **Advanced** section unlocks with Pro (or Demo Mode):

- **Correlations** — which factors track with energy and mood (tap a cell to drill into Scatter)
- **Best vs Worst Days** — what your highest- and lowest-energy days have in common
- **Scatter** — plot any factor against energy or mood with a trendline
- **Energy by Category** — average energy by workouts, alcohol, day of week, trackers, and more

More screenshots for these reports are coming. Each card shows a readiness hint ("Needs more days") when there isn't enough data yet.

---

## Entry History

### Mood Entries List

From the Menu, access "Mood Entries" to see a chronological list of all your mood, energy, and activity entries.

<img src="../images/mood-entries.png" alt="Mood entries" width="350">

Each entry shows:
- Timestamp
- Mood
- Energy level
- Activity
- Any associated notes

Swipe left on an entry to edit or delete it.

### Day End Entries

"Day End Entries" (from the Menu) shows your daily reflections—journal entries, goals, and wellness ratings.

<img src="../images/day-end-entries.png" alt="Day End entries" width="350">

This is useful for reviewing what you wrote, not just what you logged.

---

## What Patterns Look Like

After a few weeks of tracking, patterns become visible:

### Energy Rhythms
You might notice your energy consistently dips after lunch, or that weekends have different energy profiles than weekdays.

### Mood Correlations
Exercise might precede better moods. Poor sleep might precede worse ones. Social time might correlate with happiness.

### Activity Balance
The Base Chart (Menu → Analysis → Base Chart) reveals how you actually spend time versus how you think you spend it. Many people are surprised by the pie chart numbers.

### Cyclical Patterns
Some patterns are weekly (Monday blues, Friday energy). Some are monthly. Some are seasonal. The longer you track, the more cycles become visible.

---

## Tips for Pattern Recognition

**Look at weeks, not days.** Single days are noisy. Weeks show trends.

**Compare similar periods.** Compare this week to last week. This month to last month.

**Notice surprises.** When something doesn't match your expectations, pay attention.

**Don't force conclusions.** Correlation isn't causation. Notice patterns, but hold conclusions loosely.

---

[← Back to Guide](index.md) · [Next: Habits →](habits.md)
