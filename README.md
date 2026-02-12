# Shonchoy: The Everyday Expense Tracker

<p align="center">
  <img src="assets/Shonchoy.png" width = "150" height = "150" alt="Shonchoy App Icon">
</p>
<p align="center">
  <h2 align="center">Stop guessing where your money went!</h2>
</p>

<p align="center">
  <b>Fast • Offline • Frictionless</b><br>
  The only finance app designed for the "3-Tap Rule": Log an expense in under 5 seconds.
</p>

<br>

<p align="center">
  <a href="https://github.com/Ahnaf181419/Shonchoy/raw/main/Shonchoy_ExpenseTracker.apk">
    <img src="https://img.shields.io/badge/Download_APK-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white&height=40" height="45" alt="Download APK">
  </a>
</p>
<p align="center">
  <small><i>v1.0.0 • No Account Required • Free Forever!</i></small>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
</p>

---

## 🧐 Why Another Expense Tracker?

Most finance apps are **too slow**. They ask for too many details, require internet, or force you to create an account.

**Shonchoy is different.** It is built for **velocity**.

- **No Login:** Open the app and start immediately.
- **No Loading:** Everything is stored on your phone.
- **No ads:** Just you and your finances.

> _"If logging a coffee takes more than 5 seconds, you won't do it. Shonchoy fixes that."_

---

## ✨ Features You'll Actually Use

### 1. The "3-Tap" Entry System (Core)

- **Speed:** Log a transaction in < 5 seconds.
- **Custom Keypad:** Large, dedicated numeric pad (No system keyboard lag).
- **Smart Category Grid:** Automatically bubbles up your top 3 most-used categories to the top row.
- **Smart Defaults:** Auto-selects "Today" and "Now".

### 2. The Dashboard (Visuals)

- **Live Balance:** `(Income - Expense) = Current Balance`.
- **Budget Health Bar:** Color-coded progress bar (Green → Orange → Red) based on monthly spending.
- **Safe Spend Indicator:** Calculates exactly how much you can spend _per day_ for the rest of the month.
- **Spending Breakdown:** Simple Pie Chart and "Top Spenders" list.

### 3. Debt & Lending Tracker

- **IOU Management:** Separate tab for "I Owe" vs "Owes Me".
- **Net Worth Impact:** Shows a "Net Debt Position" card on the dashboard.
- **Partial Payments:** Track repayments without closing the entire debt.

### 4. Smart Tutorials (Contextual)

- **Onboarding:** "Cold Start" setup to set initial cash balance.
- **Walkthroughs:** Interactive "Coach Marks" guide users through the FAB, Budget Bar, and Swipe Actions.
- **Just-in-Time:** Teaches "Swipe to Delete" and "Swipe to add note" only after the _second_ transaction is created.

### 5. Data & Settings

- **PDF Export:** Generate professional, printable transaction reports.
- **Category Limits:** Set soft monthly limits for specific categories (e.g., Food: ৳5,000).
- **Offline First:** 100% local data ownership. No servers, no accounts.
- **Dark Mode:** System-wide support.

### 6. Budget Planner

- **New Module:** Added BudgetPlannerScreen accessible via Settings.
- **Architecture:** Implemented a separate Hive Box (budget_plan_box) to ensure planning data never interferes with actual transaction history.
- **Dynamic Dashboard:** Reused the core Dashboard UI components to visualize "Planned Income" vs. "Planned Expenses."
- **Custom Inputs:** Users can now assign budgets to specific custom names (Strings) rather than fixed Category Enums, allowing for granular planning (e.g., separating "Groceries" from "Snacks").

---

## 📱 Screenshots

<table align="center">
  <tr>
    <td align="center">
      <img src="assets/SS/01.jpeg" width="250" alt="Screen 1">
    </td>
    <td align="center">
      <img src="assets/SS/02.jpeg" width="250" alt="Screen 2">
    </td>
    <td align="center">
      <img src="assets/SS/03.jpeg" width="250" alt="Screen 3">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="assets/SS/04.jpeg" width="250" alt="Screen 4">
    </td>
    <td align="center">
      <img src="assets/SS/05.jpeg" width="250" alt="Screen 5">
    </td>
    <td align="center">
      <img src="assets/SS/06.jpeg" width="250" alt="Screen 6">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="assets/SS/07.jpeg" width="250" alt="Screen 7">
    </td>
    <td align="center">
      <img src="assets/SS/08.jpeg" width="250" alt="Screen 8">
    </td>
    <td align="center">
      <img src="assets/SS/09.jpeg" width="250" alt="Screen 9">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="assets/SS/10.jpeg" width="250" alt="Screen 10">
    </td>
    <td align="center">
      <img src="assets/SS/11.jpeg" width="250" alt="Screen 11">
    </td>
    <td align="center">
      <img src="assets/SS/12.jpeg" width="250" alt="Screen 12">
    </td>
  </tr>
</table>

---

## 📥 How to Install (Android)

Since Shonchoy is privacy-focused and open-source, you can install it directly via APK:

1.  **Download:** Click the green [**Download APK**] button at the top.
2.  **Open:** Tap the downloaded file (`Shonchoy_ExpenseTracker.apk`).
3.  **Install:** If prompted, allow "Install from Unknown Sources" (this is standard for apps outside the Play Store).
4.  **Enjoy:** Start tracking in seconds!

---

## 💬 Feedback & Support

Found a bug? Have a feature request?

- 🐛 [Report an Issue](https://github.com/Ahnaf181419/Expense-Tracker/issues)
- ⭐ **Star this repo** if you find it useful!

---

<p align="center">
  Built with ❤️ using <b>Flutter</b>.
</p>
