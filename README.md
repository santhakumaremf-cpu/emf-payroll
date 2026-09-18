# EMF Payroll Online

**Even More Foods Private Limited** – Online Payroll & Attendance System

## 🌐 Live App
**https://santhakumaremf-cpu.github.io/emf-payroll/**

*(Enable GitHub Pages first: Repo Settings → Pages → Source = Deploy from branch `main` / root)*

## Features
| Feature | Details |
|---------|--------|
| **Employees** | Add / Edit / Delete workers |
| **Attendance** | Click day cells: Present → Absent → Leave → Half |
| **Salary** | Auto calc PF, ESI, Advance, Net |
| **Advance** | Track advances & balance |
| **Export** | CSV + JSON backup |
| **Offline** | Works after first load (localStorage) |

## First-time setup (Excel data)
1. Open the app
2. Go to **Settings**
3. Click **Import JSON** and select `emf_payroll_backup.json` (from this repo or your download)
4. All 93 workers + attendance + advances will load

## How to use
1. **Employees** tab → **+ Add Worker**
2. **Attendance** → click any day cell to mark
3. **Salary** → **Recalculate All** after attendance
4. **Settings** → **Backup Data** to move to another phone/PC

## Files
- `index.html` – the app
- `data.js` – seed data (upload full version from your computer if needed)
- `emf_payroll_backup.json` – full Excel data for Import
