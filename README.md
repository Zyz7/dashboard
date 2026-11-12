# 📊 Dashboard

<img width="1402" height="847" alt="screen101800" src="https://github.com/user-attachments/assets/c44b465a-4d52-40a9-8413-03aa92d5b12b" />

An admin dashboard built as a **pure frontend project**, focused on visualizing data
through summary cards, tables and a charted reports overview.

🔗 **Live demo:** [https://dashboard-wry6.onrender.com](https://dashboard-wry6.onrender.com)

## ✨ Features

- Collapsible sidebar with multi-level navigation menus (Bootstrap collapse)
- Search bar and user avatar dropdown in the top navbar
- KPI cards with progress metrics and month-over-month change
- Users table (striped, responsive)
- Grouped bar chart for the **Reports Overview** section
- Fully responsive layout (desktop, tablet and mobile)
- No backend required — static files only

## 🛠️ Tech Stack

| Technology | Usage |
| ---------- | ----- |
| [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) | Page structure |
| [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) | Custom styles (`assets/css/style.css`) |
| [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) | Interactivity (`assets/js/app.js`) |
| [Bootstrap 5.3](https://getbootstrap.com) | Layout, grid, components (via CDN) |
| [Boxicons](https://boxicons.com) | Icon set (via CDN) |
| [Chart.js](https://www.chartjs.org) | Bar chart for reports (via CDN) |
| [Render](https://render.com) | Static site hosting |


## ⚙️ Running Locally

Since this is a static site, no build step is required. Just serve the `public/` folder:

```bash
# Option 1: with Node
npx serve public

# Option 2: with Python
python -m http.server -d public 8000
