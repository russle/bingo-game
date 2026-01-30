# Bingo Game! 🎲

[繁體中文](#繁體中文) | [English](#english)

---

## 繁體中文

一個現代化、美觀且功能強大的即時賓果抽號系統。專為活動主持、尾牙抽獎設計，支援多人同步顯示與本地/雲端雙模式。

### ✨ 功能特點

-   **雙模式支援**：
    -   **雲端同步模式**：整合 Firebase Realtime Database，抽號結果即時同步至所有連線裝置。
    -   **本地模式 (Local Mode)**：無需 Firebase 配置即可立即開始，結果儲存於瀏覽器 localStorage。
-   **即時互動**：
    -   觀眾可透過掃描右下角 **QR Code** 開啟觀看頁面 (`board.html`)，同步看到最新抽出的數字與特效。
    -   支援大螢幕投放特效，抽出號碼時自動觸發煙花特效。
-   **彈性設定**：
    -   自定義抽號範圍：可設置 **10 至 100** 之間的任意最大值。
    -   即時統計：自動計算已抽出的號碼數量與剩餘池。
    -   賓果計數器：支援即時增減賓果人數，方便主持掌控現場。
-   **現代化 UI/UX**：
    -   全響應式設計 (RWD)，適配手機、平板與電腦。
    -   精美的玻璃擬態 (Glassmorphism) 設計風格。
    -   支援空白鍵快捷抽號。
-   **輕鬆安裝**：透過網頁介面直接配置 Firebase 資費，無需手動修改任何代碼文件。

### 🚀 快速開始

1.  **準備 Firebase 專案**（若需雲端同步）：在 Firebase Console 建立專案，啟用 Realtime Database 與匿名登入。
2.  **部署方式**：將所有檔案上傳至任何靜態託管空間（如 GitHub Pages）。
3.  **開始使用**：開啟 `index.html`，根據提示輸入 Firebase 配置或選擇「本地模式」開始。

---

## English

A modern, sleek, and powerful real-time Bingo system. Designed for event hosting and lucky draws, featuring multi-device synchronization and local/cloud dual modes.

### ✨ Features

-   **Dual Mode Support**:
    -   **Cloud Sync Mode**: Integrated with Firebase Realtime Database for instant synchronization across all connected devices.
    -   **Local Mode**: Start immediately without Firebase configuration; game state is saved in the browser's `localStorage`.
-   **Interactive Experience**:
    -   Viewers can scan the **QR Code** in the bottom-right corner to open the viewer page (`board.html`) and see results in real-time.
    -   Optimized for large screen displays with automatic firework effects upon drawing a number.
-   **Flexible Configuration**:
    -   Custom Range: Set any maximum number between **10 and 100**.
    -   Real-time Stats: Automatically tracks drawn numbers and the remaining pool.
    -   Bingo Counter: Manage the number of winners in real-time to keep control of the event.
-   **Modern UI/UX**:
    -   Fully Responsive Web Design (RWD) for mobile, tablet, and desktop.
    -   Stunning **Glassmorphism** design style.
    -   Hotkeys: Support for the **Spacebar** to draw numbers quickly.
-   **Easy Setup**: Configure Firebase credentials directly through the web UI without touching the source code.

### 🚀 Quick Start

1.  **Prepare Firebase Project** (for Cloud Sync): Create a project in the Firebase Console, enable Realtime Database, and turn on Anonymous Authentication.
2.  **Deployment**: Upload all files to any static hosting service (e.g., GitHub Pages, Netlify, or Vercel).
3.  **Get Started**: Open `index.html`, follow the prompts to enter your Firebase config, or select "Local Mode" to play offline.

---

## 📂 文件結構 / File Structure
-   `index.html`: 主控端管理頁面 / Master Control Panel.
-   `board.html`: 觀眾同步頁面 / Synchronized Viewer Board.
-   `LICENSE`: MIT 授權文件 / MIT License.

## 📜 授權協議 / License
本專案採用 [MIT License](LICENSE)，歡迎自由修改與分發。
This project is licensed under the [MIT License](LICENSE).
