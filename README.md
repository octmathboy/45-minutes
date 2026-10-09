# Weekly Expense Tracker for Android & Mobile Web

An Android-optimized, mobile-first Web Application designed to track weekly spending on **Food**, **Transport**, **Housing**, **Shopping**, **Entertainment**, **Health**, and other essential expenses.

![App Features](https://img.shields.io/badge/Platform-Android%20%7C%20Mobile%20Web-indigo)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌟 Key Features

1. **Weekly Budget Overview**
   - Live progress indicator showing weekly budget consumption.
   - Dynamic budget status alerts (Green, Amber, Red when approaching or exceeding weekly limit).
   - Instant category breakdown pills for fast status checking.

2. **Categorized Expense Logging**
   - **Categories**: Food 🍔, Transport 🚌, Housing 🏠, Shopping 🛍️, Entertainment 🎬, Health 🏥, Other 📦.
   - **Quick Add (+ Floating Action Button)**: Log new transactions in seconds.
   - Store amount, date, item description, category, and payment method (Cash, Card, Mobile Pay).

3. **History & Search**
   - Filter transactions by category or time range (This Week, Last Week, This Month, All Time).
   - Full text search across item descriptions and tags.
   - Edit or delete logged expenses anytime.

4. **Visual Analytics & Insights**
   - Interactive Doughnut Chart for expense category distribution (powered by Chart.js).
   - 4-Week Spending Trend Bar Chart for week-over-week comparison.
   - Key stats: Top spending category & average daily spend.

5. **Settings & Customization**
   - Customizable weekly spending target/goal.
   - Multi-currency support (`$`, `€`, `£`, `DA`, `DH`, `₹`, `CA$`).
   - Dark Mode / Light Mode toggle.
   - Offline `localStorage` persistence.
   - Export expenses to **CSV** spreadsheet or **JSON** backup.

---

## 📱 How to Use on Android

### Option 1: Browser / Mobile Web
1. Open Chrome (or your default Android browser) and load `index.html`.
2. Tap the browser menu `⋮` and select **"Add to Home screen"**.
3. Launch the app directly from your Android home screen as a standalone application!

### Option 2: Local Development / Testing
Run a simple HTTP server in the project directory:

```bash
# Using Python
python3 -m http.server 8000
```
Open `http://localhost:8000` on your mobile browser or Android emulator.

---

## 🛠️ Built With

- **HTML5 & CSS3**
- **Tailwind CSS** (via CDN)
- **Chart.js** for mobile-responsive visual charts
- **FontAwesome 6** for crisp vector icons
- **Vanilla JavaScript (ES6)**
- **LocalStorage API** for offline data safety
