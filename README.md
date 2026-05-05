# IDE Dashboard – Sprint Management

A **single‑file, fully client‑side HTML dashboard** for managing **Sprint Projects & Tasks** in an **Industrial Design Engineering (IDE)** environment.

This dashboard includes **role‑based access**, **analytics**, **charts**, **Excel import/export**, **PDF reports**, and a **modern dark/light UI** — all without any backend.

***

## 🚀 Features

### ✅ Role‑Based Login (Client‑Side)

*   **Administrator**
    *   Full access (Add, Edit, Delete, Approve)
*   **Technician**
    *   Add & Edit items
    *   Request delete approval
*   **Viewer**
    *   Read‑only access
    *   Export reports

### ✅ Dashboard Modules

*   Overview KPIs
*   Projects & Tasks table
*   Blockers tracking
*   Approval workflow
*   Analytics & charts
*   Sprint velocity
*   Timeline view
*   Activity log
*   Excel import
*   CSV / Excel / PDF export

***

## 🧩 Tech Stack

*   **HTML5** (single file)
*   **CSS3** (CSS variables, dark/light theme)
*   **Vanilla JavaScript**
*   **Chart.js** – charts & analytics
*   **Font Awesome** – icons
*   **SheetJS (xlsx)** – Excel import/export
*   **jsPDF + AutoTable** – PDF export

✅ No backend  
✅ No database  
✅ Runs entirely in the browser

***

## 📁 Project Structure

```text
.
├── index.html   ← Entire application (HTML + CSS + JS)
└── README.md
```

***

## 🔐 Demo Login Credentials

> ⚠️ **Demo only — client‑side authentication**

| Role          | Username | Password         |
| ------------- | -------- | ---------------- |
| Administrator | admin    | `Admin@IDE2026!` |
| Technician    | tech1    | `Tech@IDE2026#`  |
| Viewer        | viewer   | `View@IDE2026$`  |

***

## 🖥️ How to Run Locally

### Option 1: Open directly

1.  Download `index.html`
2.  Double‑click the file  
    ✅ Opens in your browser

### Option 2: VS Code Live Server (recommended)

```bash
Right‑click index.html → Open with Live Server
```

***

## 🌐 Deploy on GitHub Pages (Recommended)

### ✅ User Site (Simplest & Reliable)

1.  Create a repository named **exactly**:
        <your-username>.github.io
2.  Add `index.html`
3.  Commit

✅ Access at:

    https://<your-username>.github.io

***

## 📊 Excel Import Format

Your Excel file can contain headers like:

```text
Type | Orchestra | Project Name | Status | Priority | Blockers | Start Date | End Date | Details
```

✅ Supports `.xlsx` and `.xls`  
✅ Auto‑maps common header variations  
✅ Deduplicates by project/task name

***

## 📤 Export Options

*   ✅ CSV (raw table data)
*   ✅ Excel (.xlsx)
    *   Projects sheet
    *   KPI summary sheet
*   ✅ PDF
    *   KPI overview
    *   Full table
    *   Landscape A4 layout

***

## 🎨 Theme Support

*   Dark mode (default)
*   Light mode
*   Theme preference saved in `localStorage`

***

## ⚠️ Important Notes

*   This is a **frontend‑only demo**
*   Passwords are stored in JavaScript (not secure)
*   No persistence (data resets on refresh)
*   Best suited for:
    *   Internal demos
    *   Prototypes
    *   Sprint reviews
    *   Training & planning tools

***

## ✅ Future Enhancements (Optional)

*   Backend authentication
*   Database persistence
*   Multi‑user sync
*   API‑based data source
*   Role management UI
*   Audit logs export

***

## 📜 License

This project is provided for **internal / educational use**.  
Modify and extend as needed.

***
