# 🏏 Cricket Score System (Web Version with Stats)

A modern, feature-rich web-based cricket tournament management system. This version includes a **frontend** (the website you see in your browser) and a **backend** (the engine that runs on your phone using Termux).

Create custom tournaments, simulate matches, and view detailed statistics including scorecards and Net Run Rate (NRR), all from a clean and user-friendly interface.

## ✨ Features

-   **Modern Web Interface**: Easy-to-use website that runs in your phone's browser.
-   **Detailed Scorecards**: View a full breakdown of each innings, including runs, wickets, extras, fours, and sixes.
-   **Net Run Rate (NRR)**: The points table now automatically calculates and displays the NRR for accurate team rankings.
-   **Instant Bot Simulation**: Get realistic match results in seconds.
-   **Automatic Scheduling**: A round-robin schedule is generated for you.
-   **System Reset**: A "Reset System" button to easily clear all data and start a new tournament.
-   **Cross-Device Access**: View and control the tournament from any device on the same Wi-Fi network.

---

## 📋 Prerequisites

Before you start, you will need:

1.  **An Android Phone**.
2.  **Termux**: A terminal emulator for Android.
    -   **Important**: You **must** install Termux from **F-Droid**. The version on the Google Play Store is outdated and will not work.
3.  **A Web Browser**: (e.g., Chrome, Firefox) on your phone.

---

## 🚀 Installation & Setup Guide

Follow these steps in your Termux application.

### Step 1: Update and Install Packages

First, open Termux and run the following commands to update it and install the necessary tools (`python` and `git`).

```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/Dinaaofficial/SCORE-BOT.git
cd SCORE-BOT
pip install -r requirements.txt
python backend/app.py

