# ⏱️ DSA Focus Timer (UI v1)  

![DSA Focus Timer UI](DSA_Timer/screenshot.png)  

[![Version](https://img.shields.io/badge/version-v1.0-blue)](https://github.com/)  
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/)  

A **clean and minimal UI-first Chrome extension concept** designed to help developers stay focused while solving **Data Structures & Algorithms (DSA)** problems.  

This is **Version 1**, focused purely on **layout, screen flow, and UX structure**.  
Core timer logic and data handling will be added in upcoming versions.

---

## ✨ Features (UI v1)

- 🎯 Select **problem difficulty**: Easy / Medium / Hard  
- 🔁 Choose **attempt type**:
  - First attempt (new problem)  
  - Revision (practice again)  
- ⏳ Timer action buttons (UI-ready)  
- 📊 Dedicated **Progress screen**:
  - Total attempts  
  - Solved vs Unsolved  
  - Difficulty-wise breakdown  
- 🔄 Screen switching handled using layered layout design  

---

## 🧠 Design Decisions

- **Single-page structure** – Both screens exist in the same HTML file and are controlled via CSS visibility instead of multiple pages.  
- **Overlapping screens** – Implemented using `position: relative` (parent) and `position: absolute` (screens) to stack UI screens cleanly.  
- **UI-first approach** – Focused on clarity, spacing, and structure before adding JavaScript logic.

---

## 🛠️ Tech Stack

- **HTML** – Structure  
- **CSS** – Styling & layout  
- **JavaScript** – Logic placeholder (planned for v2)

---

## 🚀 How to Run

1. Clone the repository:  
```bash
git clone https://github.com/Ayushi-Maurya2904/DSA-Focus-Timer.git
