
## OddOne | Premium Custom New Tab Dashboard

**OddOne** is a feature-rich, high-performance Chrome Extension built with React 19, TypeScript, and Vite. It completely reimagines your browser's default New Tab page into a fully customizable, production-grade productivity dashboard using an intuitive drag-and-drop grid canvas.

Designed with a premium glassmorphic aesthetic, OddOne helps you optimize your daily workflow by unifying real-time utilities, secure personal automation, and your complete Google ecosystem into a single screen.

### 🌟 Key Features

- **Dynamic Grid Workspace:** Fully responsive 12-column drag-and-drop canvas layout powered by `react-grid-layout` with seamless widget resizing and collision handling.
- **Deep Google Integration:** Built-in secure OAuth2 authentication via `chrome.identity` supporting live-syncing Google Tasks and automatic configuration backups straight to your hidden Google Drive AppData folder.
- **API-Insulated Sandbox:** Run arbitrary user-written JavaScript, custom CSS, or AI-generated widgets inside a fully secure, isolated iframe (`sandbox.html`) completely disconnected from privileged Extension APIs.
- **Premium UI & Aesthetics:** Native system glassmorphism styled with Tailwind CSS, custom dynamic time-of-day greetings, a high-visibility digital clock ticker, and live location-based weather tracking.

### 🧩 20 Built-in Ecosystem Widgets

OddOne comes packaged with 20 production-ready, interactive widgets completely implemented out-of-the-box:

1. **Google Tasks:** Live checkbox sync and inline task creation.
2. **News Aggregator:** 10 recent global stories equipped with custom keyword search filtering.
3. **Quick Access:** Immediate access to your top-visited sites via `chrome.topSites`.
4. **AI Custom Canvas:** Sandbox environment to paste code or generate live UI elements on the fly.
5. **Interactive Sticky Note:** A lightning-fast, scratchpad that persists locally.
6. **Pomodoro Timer:** Visual focus countdown block with start, pause, and reset controls.
7. **Scientific Calculator:** Complete grid-button operations for advanced arithmetic.
8. **FX Currency Converter:** Real-time matrix swapping currency pairs (e.g., USD to BDT).
9. **Weather Forecast:** Extended 5-day predictive weather metrics.
10. **Detailed Clock:** World clock dashboard with adjustable secondary time zones.
11. **System Monitor:** Diagnostic module tracking device OS and hardware architecture.
12. **RSS Feed Reader:** Custom feed rendering parsed directly from any user-provided URL.
13. **Interactive Calendar:** Full monthly view highlighting current grid metrics.
14. **Quick Dictionary:** Instant structural vocabulary definitions and syntax solver.
15. **Crypto Live Tracker:** Active market tracking data for major assets (BTC, ETH).
16. **Habit Tracker:** Matrix of daily completion checkmarks persisting across reloads.
17. **Unit Converter:** Scalable dropdown selector converting lengths, weights, and temperatures.
18. **Focus Soundboard:** Ambient background noise player (Rain, Lo-Fi loops) with toggles.
19. **Event Countdown:** High-accuracy countdown tracking events down to the exact second.
20. **Daily Quotes Generator:** Instant cycle of inspirational quotes with manual generation hooks.

### 🛠️ Tech Stack

- **Core:** React 19, TypeScript (Strict Mode), Vite
- **Architecture:** Chrome Extension Manifest V3
- **Styling:** Tailwind CSS (Glassmorphic Utilities)
- **Layout Engine:** `react-grid-layout`


## 📦 Installation & Setup

Since the production-ready compiled bundle is included directly in the repository, you can load the extension into Google Chrome immediately.

### 1. Clone the Repository

Open your terminal or command prompt and clone the repository to your local machine:

```bash
git clone [https://github.com/ShaharearSabbir/OddOne.git](https://github.com/ShaharearSabbir/OddOne.git)

```

*(Alternatively, you can click the green **Code** button at the top of this page and select **Download ZIP**, then extract it on your computer).*

---

### 2. Load the Extension into Google Chrome

1. Open Google Chrome and navigate to the Extensions management page by typing **`chrome://extensions/`** into your URL bar and hitting Enter.
2. In the top-right corner of the page, toggle the **Developer mode** switch to **ON**.
3. Click the **Load unpacked** button that appears in the top-left toolbar.
4. In the file explorer window, select to your cloned/extracted `OddOne` folder

**🎉 Success!** The **OddOne Custom New Tab Dashboard** is now active in your browser. Open a blank new tab to check out your brand new workspace workspace canvas.