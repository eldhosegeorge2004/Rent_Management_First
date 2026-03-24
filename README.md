# 🏠 Rent Management Dashboard

A lightweight, single-page web application to manage rental properties, track tenant payments, and visualize rent collection — all stored locally in your browser.

🔗 **Live Demo:** [https://eldhosegeorge2004.github.io/Rent_Management_First/](https://eldhosegeorge2004.github.io/Rent_Management_First/)

---

## 📸 Screenshots

### 🏠 Dashboard with Tenant Data
![Rent Management Dashboard](https://raw.githubusercontent.com/eldhosegeorge2004/Rent_Management_First/main/screenshots/dashboard_clean.png)

### 📊 Live Dashboard View
![Rent Management Dashboard - Live](https://raw.githubusercontent.com/eldhosegeorge2004/Rent_Management_First/main/screenshots/dashboard_light.png)

### 🌑 Dark Mode
![Rent Management Dashboard - Dark Mode](https://raw.githubusercontent.com/eldhosegeorge2004/Rent_Management_First/main/screenshots/dashboard_dark.png)

### ➕ Add New Tenant Form
![Add New Tenant Form](https://raw.githubusercontent.com/eldhosegeorge2004/Rent_Management_First/main/screenshots/add_tenant_form.png)

---

## ✨ Features

| Feature | Description |
|---|---|
| 📊 **Summary Cards** | Instantly see Total Rent Collected, Expected Monthly Rent, and Total Collected This Year |
| 👥 **Tenant Management** | Add, remove, and manage tenants with name, rent amount, and avatar photo |
| ✅ **Payment Tracking** | Mark rent as paid with a single checkbox; date is auto-recorded |
| 🖼️ **Avatar Support** | Upload tenant profile photos or fall back to initials-based avatars |
| 📉 **Pie Chart** | Visual breakdown of collected vs. pending rent using Chart.js |
| 📄 **CSV Export** | Export all tenant payment data as a `.csv` file with one click |
| 🌙 **Dark Mode** | Toggle between light and dark themes; preference is saved automatically |
| 📈 **Auto Rent Increase** | Applies a 5% annual rent increase automatically at the start of each new year |
| 🔔 **Unpaid Alerts** | Browser notification on the 30th/31st if any tenant has unpaid rent |
| 💾 **LocalStorage** | All data persists between sessions — no backend or database needed |

---

## 🚀 Getting Started

### Option 1: Use the Live Demo
Visit the hosted version directly:
👉 [https://eldhosegeorge2004.github.io/Rent_Management_First/](https://eldhosegeorge2004.github.io/Rent_Management_First/)

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/eldhosegeorge2004/Rent_Management_First.git

# Navigate to the project folder
cd Rent_Management_First

# Open index.html in your browser
# (Double-click index.html, or use a local server like Live Server in VS Code)
```

No build steps, no dependencies to install — just open `index.html` in any modern browser!

---

## 🛠️ Tech Stack

- **HTML5** — Structure and semantic markup
- **CSS3** — Custom styling with gradients, transitions, and dark mode support
- **Vanilla JavaScript** — All logic, DOM manipulation, and LocalStorage management
- **[Chart.js](https://www.chartjs.org/)** — Pie chart for rent collection visualization

---

## 📋 How to Use

1. **Add a Tenant** — Click `+ Add New Tenant`, fill in the name, rent amount, and optionally upload a photo, then click `Add Tenant`.
2. **Mark Rent as Paid** — Check the checkbox in the `Paid` column for a tenant. The date is recorded automatically.
3. **View Summary** — The cards at the top update in real time showing total collected, expected, and yearly totals.
4. **Export Data** — Click `📄 Export CSV` to download all tenant data as a spreadsheet.
5. **Toggle Dark Mode** — Click `🌙 Toggle Dark Mode` to switch themes. Your preference is saved.
6. **Remove a Tenant** — Click `Remove` in the Actions column *(only available for unconfirmed/unpaid tenants)*.
7. **Update Avatar** — Click `Update Photo` in the Actions column to change a tenant's profile picture.

---

## ⚙️ Key Behaviours

- **Annual Rent Increase:** At the start of each new calendar year, all tenant rents are automatically increased by **5%** and payment statuses are reset.
- **Payment Confirmation Lock:** Once a tenant's rent is confirmed as paid, they cannot be removed — this prevents accidental data loss.
- **Yearly Total:** The "Total Collected This Year" card only sums up payments made within the current calendar year.

---

## 📁 Project Structure

```
Rent_Management_First/
├── index.html       # Entire application — HTML, CSS & JS in one file
└── README.md        # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 👨‍💻 Author

**Eldhose George**
- GitHub: [@eldhosegeorge2004](https://github.com/eldhosegeorge2004)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
