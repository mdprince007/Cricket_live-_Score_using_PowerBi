# Cricket_live-_Score_using_PowerBi
A live cricket score dashboard built in Power BI using HTML, CSS, and DAX. It dynamically displays match cards for All, Live, and Result games with team logos, scores, and modern interactive design inspired by real-time sports apps.


 ## Dashboard Preview
<img width="1162" height="504" alt="Dashboard" src="https://github.com/mdprince007/Cricket_live-_Score_using_PowerBi/blob/main/live_score_update.png" />
A fully **dynamic and visually interactive Cricket Dashboard** built in **Power BI** using **HTML + CSS + DAX**.  
It displays **live, upcoming, and result-based cricket matches** in a modern card layout — just like a real-time sports app interface.

---

## 🚀 Project Overview

This project visualizes **Bangladesh Cricket Board’s live match data** in a **web-style dashboard interface** within Power BI.  
It dynamically renders match cards using HTML, CSS, and DAX expressions and provides **real-time filtering** for:
- 🟢 **Live Matches**
- 🧾 **Results**
- 🌍 **All Matches**

Each match card shows:
- Match time and type (T20, ODI, Test)
- Team logos, names, and scores
- Live or Finished status
- Series name and schedule
- Smooth animation and filter transitions

---

## 🧠 Key Features

✅ **HTML + CSS inside DAX Measure** — Custom layout with interactive design  
✅ **Dynamic Filter Buttons** — Show All, Live, or Finished matches instantly  
✅ **Animated Card Layout** — Responsive grid using inline CSS  
✅ **Custom Team Logos** — Pulled directly from live API links  
✅ **Auto-Update Simulation** — Mimics real-time match progress  
✅ **Modern UI** — Green gradient background & Bangladesh theme  

---

## 🛠️ Tools & Technologies

| Tool / Language | Purpose |
|------------------|----------|
| **Power BI** | Data visualization platform |
| **DAX** | Logic and HTML embedding |
| **HTML5 & CSS3** | Dashboard UI and animations |
| **JavaScript (Inline)** | Dynamic rendering and filters |
| **CricAPI / JSON Data** | Source for live cricket data |

---

## ⚙️ How It Works

1. **Data Source:**  
   Match data fetched via cricket API or CSV containing live match info.  

2. **DAX Measure:**  
   HTML and CSS are embedded in a DAX measure to render each match dynamically.  

3. **HTML Viewer in Power BI:**  
   Custom visual used to render HTML cards inside the report.  

4. **Filtering System:**  
   Users can click buttons (All, Live, Results) to view specific match types.  

---

## 💡 Dashboard Sections

### 🎯 Header
Displays **Bangladesh Cricket Board Dashboard** with animated “tiger roar” text.

### 🧩 Filter Buttons
Interactive buttons to switch between *All / Live / Results* matches dynamically.

### 🏆 Match Cards
Each card includes:
- Team names and flags  
- Current score and overs  
- Match type (T20 / ODI / Test)  
- Series name and date  
- Match status: Live 🔴 or Finished ✅  

---

## 🖼️ Sample Output

| Match Type | Status | Example |
|-------------|---------|---------|
| T20 | 🟢 Live | BAN vs WI — BAN 145/6 (17.3) |
| ODI | ✅ Finished | AUS 256/4 (43.2) |
| Test | ✅ Result Declared | PAK won by 90 runs |



