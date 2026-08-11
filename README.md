# 📱 Google Play Store Analytics Dashboard

An executive-level Power BI dashboard analyzing 7,000+ Android apps from the Google Play Store. This interactive dashboard provides end-to-end market insights—covering overall market volume, category performance, user rating distributions, age ratings, monetization strategies (Free vs. Paid), and technical app size drivers.

---

## 📂 File Info

* **Dashboard File:** `Google_Play_Store_Analytics.pbix` *(Open with Power BI Desktop)*

---

## 📊 Data Model & Fields

* **`Play_Store_Data`** — Main fact table containing app attributes, install volume, user feedback, monetization models, and technical specifications.
  * `App` — Unique name of the application.
  * `Category` — Market classification (e.g., GAME, FAMILY, TOOLS).
  * `Rating` — User rating score on a 1.0 – 5.0 scale.
  * `Reviews` — Total count of user reviews.
  * `Size (MB)` — App file size in Megabytes.
  * `Installs` — Total download volume (aggregated sum).
  * `Type` — Business model classification (`Free` vs. `Paid`).
  * `Content Rating` — Target audience restriction (e.g., Everyone, Teen, Mature 17+).
  * `Android Ver` — Minimum required Android OS version.

---

## 🖥️ What's on the Dashboard

### 1. Executive KPI Cards (Top Banner)
* **Count of App (`7,003K`)** — Total unique applications analyzed in the dataset.
* **Sum of Installs (`31bn`)** — Total combined downloads across all applications.
* **Average Rating (`4.16`)** — Overall platform user satisfaction score on a 1.0 – 5.0 scale.

### 2. Category & Market Demand (Center Section)
* **Most Popular App Category (Top Left):** Horizontal Clustered Bar Chart highlighting top categories by total downloads, heavily dominated by **GAME** (11Bn installs), followed by **FAMILY** and **TOOLS**.
* **User Rating Distribution (Top Center):** Area Chart showcasing user sentiment density across the 1.0 – 5.0 rating scale, peaking sharply around **4.0 – 4.5**.
* **Apps Share by Content Rating (Top Right):** Donut Chart breaking down apps by target audience, with **Everyone (84.52%)** forming the vast majority of the market.

### 3. Monetization & Technical Drivers (Bottom Section)
* **App Size (MB) vs Total Installs (Bottom Left):** Scatter Plot analyzing whether file size impacts adoption, plotted on a logarithmic Y-axis comparing `Free` vs. `Paid` apps.
* **Market Share: Free vs Paid Apps (Bottom Center):** Stacked Bar Chart illustrating total download distribution between business models, proving massive dominance of **Free apps (~31Bn installs)** over Paid apps.
* **Top Most Downloaded Apps (Bottom Right):** Horizontal Leaderboard displaying the Top 5 most downloaded applications (**Subway Surfers**, **Candy Crush Saga**, **UC Browser**, etc.), ranked cleanly using user reviews to handle tie-breakers.

---

## 🎛️ Filters & Interactivity

* **Category Dropdown (Top Right Slicer):** Filter the entire dashboard by specific app industries (e.g., GAME, PRODUCTIVITY, TOOLS).
* **Android Ver Dropdown:** Isolate app metrics based on minimum supported Android OS versions.
* **Type Buttons (`Free` / `Paid`):** Quick toggle buttons to instantly compare free vs. paid app ecosystem behavior.
* **Cross-Filtering:** Click on any bar segment, donut slice, or scatter plot point to dynamically slice metrics across all other visual charts on the page.

---

## 🚀 How to Use

1. Download and open `Google_Play_Store_Analytics.pbix` in **Power BI Desktop**.
2. Use the **Category**, **Android Ver**, or **Type** slicers on the top-right panel to filter down into specific market niches.
3. Hover over data points, bar charts, or donut segments to inspect exact values in detailed tooltips.
4. Click anywhere on the white canvas area to clear current selections and restore default view settings.
