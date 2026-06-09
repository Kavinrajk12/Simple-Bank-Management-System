# 🏦 NexBank — Management System

A sleek, dark-themed **browser-based bank account management system** built with pure HTML, CSS, and JavaScript. No backend, no database — everything runs client-side in a single file.

## 🚀 Live Demo

Open `index.html` in any modern browser — zero setup required.

## 🖥️ Screenshots

> Setup screen → Dashboard → Deposit/Withdraw modals → Transaction history

## ✨ Features

- 🧾 **Account Setup** — Enter holder name, account number & initial balance
- 💰 **Deposit** — Add funds with instant balance update
- 💸 **Withdraw** — Withdraw funds with insufficient-balance guard
- 📊 **Balance Check** — Large-display balance modal
- 🪪 **Account Details** — View all account info at a glance
- 🕒 **Transaction History** — Timestamped log of all deposits & withdrawals
- 🔔 **Toast Notifications** — Success/error feedback on every action
- 🔒 **Session Close** — Reset app back to setup screen
- ⌨️ **Keyboard Shortcuts** — Enter to confirm, Escape to close modals

## 🗂️ Project Structure

```
nexbank-management/
├── index.html     # Full app — self-contained (HTML + CSS + JS)
├── README.md      # This file
├── LICENSE        # MIT License
└── .gitignore     # Git ignore rules
```

## 🛠️ Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/nexbank-management.git

# Open in browser — no server needed
open index.html
```

## 💡 How to Use

| Step | Action |
|------|--------|
| 1 | Enter your **Name**, **Account Number**, and **Initial Balance** |
| 2 | Click **Open Account** to enter the dashboard |
| 3 | Use the action cards to **Deposit**, **Withdraw**, check **Balance**, or view **Details** |
| 4 | All transactions appear in the **Transaction History** log |
| 5 | Click **Close Session** to reset and start a new account |

## 🎨 Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, gradients, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Syne, DM Mono |

## ⚠️ Notes

- Data is **in-memory only** — refreshing the page resets all data
- Currency displayed in **Indian Rupees (₹)** with `en-IN` locale formatting
- No authentication — intended as a demo / educational project

## 📄 License

MIT — free to use, modify, and distribute.
