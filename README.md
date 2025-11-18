# 🌲 Wood CFT Calculator
*A modern, responsive, and feature-rich tool for timber merchants, carpenters, and inventory managers.*

The **Wood CFT Calculator** is a lightweight Single Page Application (SPA) that simplifies the daily task of calculating timber volume in **Cubic Feet (CFT)**. It provides instant calculations, offline data storage, smart entry merging, and professional A4 print reports — all directly in your browser.

---

## 🚀 Overview
Built with **Vanilla JavaScript** and **Bootstrap 5**, this tool replaces manual calculations with a fast and intuitive workflow. No installation required.

---

## ✨ Features

### 🧮 Smart Entry & Calculation
- **Real-Time CFT Calculation** as you type.
- **Smart Merging:** Identical (Length × Width × Thickness) entries are merged automatically by increasing quantity.
- **Field Locking:** Lock any input field 🔒 (e.g., Width, Thickness) for rapid repetitive entry.

---

### 🛠️ Data Management
- **Auto-Save:** All entries are saved instantly using `localStorage`.
- **Backup & Restore:** Export your data as a `.txt` file and restore it anywhere.
- **Live Search:** Filter results instantly.
- **Edit & Delete:** Clean, modal-based editing and deletion.

---

### 🎨 Modern UI/UX
- **Dark Mode:** Enabled by default; toggle available. Preference is saved.
- **Fully Responsive:** Works smoothly on mobile, tablet, and desktop.
- **Keyboard Friendly:** Auto-focus and Enter-key submission for fast data entry.

---

### 🖨️ Professional Reporting
- **Print-Optimized A4 Layout:** Clean columnar format for logs and entries.
- **Automatic Totals:** Handles page breaks with **Brought Forward** & **Carried Forward** values.

---

## 🛠️ Tech Stack
- **HTML5**, **CSS3**, **JavaScript (ES6+)**
- **Bootstrap 5.3**
- **Bootstrap Icons**
- **LocalStorage API**

---

## 📖 How to Use

### ▶️ Launch
Open **index.html** in any modern browser. No installation or server needed.

### ➕ Add Entry
1. Enter **Quantity (Nos)**
2. Enter **Length (ft)**
3. Enter **Width (in)** and **Thickness (in)**
4. Press **Enter** or click **Add**

### 🔒 Lock Fields
Click the lock 🔒 icon next to any input to freeze its value for subsequent entries.

### ✏️ Manage Entries
- Click **✏️ Edit** to modify an entry  
- Click **🗑️ Delete** to remove an entry  

### 🖨️ Print Report
Click **Print** to open the formatted A4 print preview.

### 💾 Backup & Restore
- **Backup:** Export your entire dataset as a `.txt` file.  
- **Restore:** Import the file on any device to resume your work.
