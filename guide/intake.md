# Intake (Pro)

Intake is a structured way to log what you consume — coffee, tea, water, vitamins, medications, alcohol, and anything else — with amounts and timestamps. Unlike typing `t caf 100` into a note, intake events live in their own database table, so you can review a clean daily list and spot patterns alongside mood and energy.

Intake is **Pro only**. Enable it in **Settings → Appearance → Intake Tab on Add**.

---

## Intake Library

Before you log anything, define what you might consume in the **Intake Library** — a catalog of items, not consumption records.

Access: **Menu → Extras → Intake Library**.

<img src="../images/intake-library.png" alt="Intake Library grouped by category" width="350">

### Item types

**Single items** — one substance with a default amount and unit. Examples: Coffee (1 cup), Vitamin C (200 mg), Ibuprofen (400 mg). When you log, you can override the amount (e.g. 2 cups when the default is 1).

**List items** — a titled bundle of lines you take together. Example: "Daily Supplements" with Vitamin C, Vitamin D, and Magnesium on separate lines. Logging a list records a single "took it" checkmark — no quantity.

### Categories

Each item belongs to one category for grouping and color:

- **Caffeine** — coffee, tea, energy drinks
- **Vitamins / Supplements**
- **Medication**
- **Alcohol**
- **Other** — water, food, anything else

On first open, the library seeds Coffee, Tea, Water, and a Daily Supplements list. Edit, deactivate, or delete them freely.

Tap **+** to add items. Tap a row to edit. Swipe left to delete (past intake logs that referenced the item are preserved with their name and amount).

---

## Logging intake

### From the Add dialog

When **Intake Tab on Add** is enabled, the Note/Tracker panel gains a third sub-tab: **Intake**.

<img src="../images/add-intake.png" alt="Add dialog Intake tab with item chips and quantity controls" width="350">

1. Pick an item from the horizontal chip list (grouped by category).
2. For **single items** — adjust quantity with − / + or type a number (e.g. 1.5).
3. For **list items** — confirm with a checkmark preview; no quantity.
4. Tap **Add Intake** — saves immediately with the dialog's timestamp. The dialog stays open so you can log multiple items in one visit.
5. **Today's Intake** below the button shows everything logged today with times; tap ✕ to delete an entry.

Intake events are separate from notes and tracker entries. They do not use the Save button — each **Add Intake** tap writes its own event.

### From Day End

When intake is enabled, **Day End** includes a collapsible **Day Intake** section alongside Day Trackers — a quick way to log or review today's consumption without opening the full Add dialog.

<img src="../images/day-end-with-intake.png" alt="Day End with Day Trackers and Day Intake grouped" width="350">

---

## Reviewing intake

**Menu → Entries → Intake** opens a chronological list of all intake events, grouped by day.

<img src="../images/intake-entries.png" alt="Intake Entries list grouped by day" width="350">

Swipe or tap to delete entries you logged by mistake.

---

## Intake vs Trackers

Both can capture caffeine or supplements, but they work differently:

| | **Intake** | **Event Trackers** |
|---|---|---|
| Data | Structured `intake_events` table | Notes with `t key value` prefix |
| Setup | Intake Library items | Tracker definitions with keys |
| Logging | Add dialog Intake tab or Day End | Note text, Tracker tab, or grid |
| Best for | Named substances with units (mg, cups, L) | Flexible shorthand, custom keys |

Many people use **Intake** for daily coffee, vitamins, and meds, and **Trackers** for symptoms or one-off events. Pro Setup mentions both when you subscribe.

---

## Setup checklist

1. Subscribe or restore Pro (or try **Demo Mode** to preview).
2. **Settings → Appearance → Intake Tab on Add** — turn on.
3. **Menu → Extras → Intake Library** — customize your catalog.
4. Log from **Add (+) → Intake** tab or **Day End → Day Intake**.
5. Review in **Menu → Entries → Intake**.

---

[← Back to Guide](index.md) · [Pro Features](pro-features.md) · [Day Launch & Day End](day-routines.md)
