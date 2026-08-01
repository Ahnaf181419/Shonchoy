# Shonchoy — User Guide

> A complete guide to Shonchoy, your offline-first expense tracker.

---

## Table of Contents

1. [Getting Started](#1-getting-started)
2. [Adding Transactions](#2-adding-transactions)
3. [Viewing Your Data](#3-viewing-your-data)
4. [Mascot Chat](#4-mascot-chat)
5. [Managing Categories](#5-managing-categories)
6. [Managing Accounts](#6-managing-accounts)
7. [Bill Splitter](#7-bill-splitter)
8. [Subscriptions](#8-subscriptions)
9. [Savings Goals](#9-savings-goals)
10. [Budget Planner](#10-budget-planner)
11. [Debts & Lending](#11-debts--lending)
12. [App Lock & Security](#12-app-lock--security)
13. [Themes](#13-themes)
14. [Data, Backup & Export](#14-data-backup--export)
15. [Settings](#15-settings)
16. [Upgrading to Pro](#16-upgrading-to-pro)
17. [Tips & Tricks](#17-tips--tricks)
18. [Troubleshooting](#18-troubleshooting)
19. [Quick Reference](#19-quick-reference)

---

## 1. Getting Started

### First Launch (Onboarding)

When you first open Shonchoy, a short setup gets you tracking in under a minute:

1. **Enter your current balance** — this is the money you have right now (cash + bank). It creates your first income transaction, "Initial Balance," so your dashboard is accurate from second one.
2. **Set a monthly budget** *(optional)* — your spending target. Change it any time in Settings.
3. Tap **Get Started**.

### The Home Screen

After setup you land on the **Dashboard**, which shows:

- Your **balance** for the selected month
- **Income** and **Expenses** totals
- **Net worth** across all accounts
- A **budget health bar** and your daily **safe-to-spend**
- A **donut chart** of spending by category
- Your **transaction list**

An in-app **tutorial** highlights the key controls on first run — you can replay it from Settings.

---

## 2. Adding Transactions

### The 3-Tap Quick Entry

Shonchoy logs an expense in under 5 seconds:

```
Tap 1: Tap the + button (FAB)
Tap 2: Type the amount
Tap 3: Tap a category → Saved
```

### Step-by-Step

1. **Open the entry screen** — tap the floating **+** button.
2. **Enter the amount** on the custom keypad.
   - Need math? Type an expression like `100+50*2` and it evaluates to `200`.
   - Use `⌫` to delete.
3. **Choose the type** — **Expense** (default), **Income**, or **Transfer** (appears only with 2+ accounts).
4. **Pick a category** — tapping one saves instantly. Your top three most-used categories float to the first row, so the ones you need are always within reach.
5. *(Optional)* **Select an account** — defaults to your chosen default account.
6. *(Optional)* **Add a note**, set a **date**, or mark it **recurring** (auto-copied each new month).

### Transfers

To move money between accounts:

1. Toggle to **Transfer**.
2. Pick the **From** and **To** accounts.
3. Enter the amount, and optionally add a **transfer fee**.

### Recurring Transactions

Mark a transaction **recurring** and Shonchoy automatically creates a copy at the start of each new month — no re-entry.

### Edit & Delete with Swipes

- **Swipe right** on a transaction to add or edit a note.
- **Swipe left** to reveal **Edit** and **Delete**. (Transfers reveal Delete only.)
- Deleted items go to the **Trash** for 30 days — see [§14](#14-data-backup--export) to undo.

---

## 3. Viewing Your Data

### Dashboard Overview

| Element | What it shows |
|---------|---------------|
| **Balance** | Income − Expenses for the month |
| **Net Worth** | Sum across all accounts |
| **Budget Bar** | How much of your monthly budget is spent (green / amber / red) |
| **Safe to Spend** | (Budget − Spent) ÷ days left this month |

### Month Navigation

Use the **← / →** arrows to move between months. The current month and year show in the header.

### Transaction List

Transactions group by day (**Today**, **Yesterday**, date…). Each row shows the category icon, name, amount (green = income, red = expense), and any note.

### Donut Chart

Each slice is a category, sized by spend. Tap a slice to open **Category Insights**.

### Category Insights

A deep dive on one category:

- **Daily spending** line chart
- **Stats grid** — total, average, largest, % of month
- **Filtered transaction list**

### Statistics *(Pro)*

Open Statistics for the long view: 12-month income/expense trends, median and 90th-percentile spending, your top merchants, and your five largest transactions in the selected range. (Free users see a preview; upgrade to unlock the full suite — see [§16](#16-upgrading-to-pro).)

---

## 4. Mascot Chat

Prefer typing to tapping? Open **Chat** and just write naturally:

> _"spent 250 on groceries"_
> _"salary 45000"_

Shonchoy parses the amount and category and logs it. **Quick-add cards** surface your recurring merchants for one-tap entry, and a raccoon mascot reacts to your spending.

> Free tier: **3 chats per day**. Pro: unlimited.

---

## 5. Managing Categories

### Default Categories

Nine come pre-installed:

| Category | Icon | Color |
|----------|------|-------|
| Food | Restaurant | Orange |
| Transport | Bus | Blue |
| Shopping | Bag | Purple |
| Entertainment | Movie | Yellow |
| Bills | Receipt | Teal |
| Health | Heart | Red |
| Education | School | Indigo |
| Salary | Wallet | Green |
| Other | More | Grey |

### Add / Edit / Delete

From **Settings → Categories**:

- **Add** — name, icon, color, and an optional **spending limit**.
- **Edit** — tap any category to change its details.
- **Delete** — choose to **reassign** its transactions to another category, or **remove** the category tag entirely.

### Category Spending Limits

Give a category a monthly limit and it warns you when exceeded — with support for daily, weekly, monthly, or yearly intervals and optional rollover of unused budget.

---

## 6. Managing Accounts

Track money across every place you keep it.

### Adding an Account

1. Go to **Settings → Accounts** (or tap **Manage** on the home accounts row).
2. Tap **+ Add Account**.
3. Enter the name, **type**, and starting balance; pick an icon and color.

### Account Types (currency-aware)

The type list adapts to your currency. With **BDT** selected you get bKash, Nagad, Rocket, Upay, DPS, and FDR; with other currencies you get the global set (Cash, Bank, Debit Card, Credit Card, PayPal, Mobile Wallet, and more).

### Credit Cards

For **Credit Card** accounts, set a credit limit, statement balance, minimum payment, and due day. Shonchoy shows your card usage and warns you as you approach the limit.

### Account History & Transfers

- Tap an account for its full transaction history.
- See [§2 Transfers](#transfers) for moving money between accounts.

---

## 7. Bill Splitter

Split a bill with friends and figure out who owes whom — with the fewest repayments.

### Create a Group

1. Open **Bill Splitter** (from Settings or Tools).
2. Create a **Group** (persistent) or a **Quick Split** (one-off).
3. Add participants. ("You" are included automatically.)

### Record a Bill

1. Add a bill to the group with a description and total.
2. Record **who paid how much**.
3. Choose a split method: **Equal**, **Custom amounts**, **Percentage**, or **Shares**.

### Settle Up

Shonchoy calculates everyone's net balance and suggests a **minimal set of settlements** — the smallest number of payments that clears all debts. Optionally link a settlement to an expense in your main ledger.

---

## 8. Subscriptions

Never lose track of a recurring charge.

### Add a Subscription

1. Open **Subscriptions** (from Settings or Tools).
2. Tap **+** and enter the name, price, and **billing cycle** (every N days/weeks/months/years).
3. Optionally add a **trial end date**, notes, and a payment method.

### Auto-Record

On each renewal date, Shonchoy can automatically create the expense for you (skipped during a free trial). Missed periods while the app was closed are caught up automatically.

### Lifecycle

- **Active** — bills normally.
- **Paused** — freezes billing.
- **Cancelled** — stops billing but keeps history.

The dashboard card shows your monthly and yearly subscription burn and the next renewal.

---

## 9. Savings Goals

1. Open **Savings** (piggy-bank icon in the home app bar).
2. Tap **+ Add Goal** — name it, set a target.
3. **Deposit** or **Withdraw** with a note; each move is logged.

Traffic-light progress bars (red < 20%, amber 20–60%, green > 60%) keep you motivated. Goals roll over month to month.

---

## 10. Budget Planner

Zero-based budgeting: give every dollar a job.

1. Open **Budget Planner** (from Settings).
2. Add **planned income** and **planned expense** items with custom names.
3. The planner shows your **unassigned balance** — the gap between planned income and planned expenses.
4. A pie chart compares planned expenses at a glance.

Pair this with per-category limits ([§5](#category-spending-limits)) for fine control.

---

## 11. Debts & Lending

Track money you owe and money owed to you.

1. Open **Debts & Lending**.
2. Tap **+ Add Debt** and choose **I Owe** or **Owes Me**.
3. Enter the person, amount, optional due date, and note.

For repayments, open a debt and **Record a Payment** with an amount and note. Each debt keeps a full payment timeline and can be marked **settled**. The dashboard's **Net Debt Position** card summarizes where you stand.

---

## 12. App Lock & Security

Protect Shonchoy with a PIN or your fingerprint/face.

1. Go to **Settings → Security**.
2. Enable **App Lock** and set a 4-digit PIN.
3. Optionally enable **Biometric** unlock.

Your PIN is stored as a **salted SHA-256 hash** in your device's secure hardware storage (Android Keystore / iOS Keychain) — never in plain text. Repeated wrong attempts trigger an escalating lockout (5s → 10s → 30s → 60s → 5min). The app re-locks when it returns from the background.

**Forgot your PIN?** Keep entering attempts — after several wrong tries a **"Forgot PIN?"** link appears that lets you reset the lock.

---

## 13. Themes

1. Go to **Settings → Theme**.
2. Pick from **Fresh Teal**, **Midnight Ocean**, **Cozy Walnut**, or **Iris Lavender**.
3. Toggle **Dark Mode** on or off.

**Fresh Teal** is free; the other three themes are part of **Pro** (see [§16](#16-upgrading-to-pro)).

---

## 14. Data, Backup & Export

### CSV Import / Export

- **Export** creates a full backup (accounts, categories, transactions, debts, savings, subscriptions) as a CSV file you can share or save.
- **Import** restores from a backup file. Missing accounts and categories are created automatically. *(Free tier imports are subject to the account/category limits — see [§16](#16-upgrading-to-pro).)*

### PDF Reports

Generate a polished report (summary, category breakdown, account balances, full transaction table) for **All Time**, **This Month**, **Last Month**, **Last 3 Months**, or a **Custom range**.

### Google Drive Backup *(Pro)*

Encrypt and back up your data to **your own** Google Drive — nothing ever touches Shonchoy's servers. Configure it under **Settings → Cloud Backup**.

### Trash (Undo)

Anything you delete goes to the **Trash** for **30 days**, where you can restore it (with side effects reversed) or purge it for good. Open Trash from Settings.

### Reset All Data

To start fresh: **Settings → Reset All Data**. This permanently deletes everything — back up first.

---

## 15. Settings

Tap the **gear** icon on the home screen.

| Setting | What it does |
|---------|--------------|
| **Profile** | Your name and avatar |
| **Dark Mode** | Toggle dark theme |
| **Theme** | Pick one of four themes (3 are Pro) |
| **Currency** | Change currency (drives account types) |
| **Monthly Budget** | Set your spending target |
| **Haptics** | Toggle vibration feedback |
| **Spending Humor** | Toggle witty post-spend messages |
| **App Lock / Biometric** | PIN + fingerprint/face protection |
| **Accounts** | Manage accounts |
| **Categories** | Manage categories |
| **Bill Splitter** | Split bills with friends |
| **Subscriptions** | Track recurring payments |
| **Savings** | Savings goals |
| **Budget Planner** | Zero-based budgeting |
| **Debts & Lending** | Loans and IOUs |
| **Cloud Backup** *(Pro)* | Google Drive backup |
| **Export / Import** | CSV and PDF tools |
| **Trash** | Restore or purge deleted items |
| **Upgrade to Pro** | See [§16](#16-upgrading-to-pro) |

---

## 16. Upgrading to Pro

Pro unlocks the limits and adds the power features:

| | Free | Pro |
|---|:---:|:---:|
| Log expenses & income | Unlimited | Unlimited |
| Accounts | 5 | ∞ |
| Categories | 20 | ∞ |
| Savings goals | 1 | ∞ |
| Subscriptions | 1 | ∞ |
| Mascot chat | 3 / day | ∞ |
| PDF reports | 1 / month | ∞ |
| Themes | 1 (Fresh Teal) | All 4 |
| Statistics | — | ✓ |
| Google Drive backup | — | ✓ |

Open **Settings → Upgrade to Pro** to purchase via Google Play Billing. Your purchase is tied to your Google account.

---

## 17. Tips & Tricks

- **Swipe right** on a transaction → add/edit a note.
- **Swipe left** → Edit or Delete.
- **Type math** in the amount field — `100+50*2` becomes `200`.
- **Smart categories** — the more you use a category, the higher it climbs.
- **Mark recurring** so monthly bills clone themselves.
- **Offline first** — core tracking needs no internet and no account; only the Pro purchase and optional Google Drive backup use a connection. No data leaves your phone unless you back it up.

---

## 18. Troubleshooting

**App won't open**
Force close and reopen; restart your phone; reinstall (back up first — your data is local).

**Transactions don't appear**
Check the month with the ← / → arrows; check you're not filtered to Income/Expense only.

**Budget not working**
Ensure a monthly budget is set in Settings and that spending falls in the current month.

**Forgot PIN**
Keep entering wrong PINs until the **"Forgot PIN?"** link appears (after several attempts). Tap it, confirm the reset, then set a new PIN in **Settings → Security**.

**Need help?**
- Report it on GitHub: **[github.com/Ahnaf181419/Shonchoy/issues](https://github.com/Ahnaf181419/Shonchoy/issues)**
- Or email the developer: **muhammad.ahnaf.sarker@gmail.com**

---

## 19. Quick Reference

| Action | How |
|--------|-----|
| Add expense | **+** → amount → category |
| Add income | **+** → amount → toggle Income → category |
| Transfer | **+** → toggle Transfer → From/To → amount |
| Edit / delete | Swipe a transaction **left** |
| Add note | Swipe a transaction **right** |
| Change month | Tap ← / → in the header |
| View accounts | Tap **Manage** on home |
| Split a bill | Settings → Bill Splitter |
| Lock the app | Settings → Security → App Lock |
| Export data | Settings → Export / Import |
| Back up to Drive | Settings → Cloud Backup *(Pro)* |

---

*Shonchoy — Stop guessing where your money went.*
