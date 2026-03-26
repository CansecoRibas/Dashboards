# 📊 Dashboards

Public showcase of interactive dashboards and visualizations generated from the Data Management project. This repository serves as the public-facing companion to the private `Data_Management` repository, making visual outputs accessible without exposing sensitive data.

## 🌐 Live Site

The dashboards are published via GitHub Pages and can be accessed at:

**[https://cansecoribas.github.io/Dashboards/](https://cansecoribas.github.io/Dashboards/)**

## 📁 Repository Structure

```
Dashboards/
├── index.html              # Main landing page (GitHub Pages entry point)
├── dashboards/             # Dashboard HTML files organized by project
│   └── ...                 # Interactive HTML dashboards (generated from R)
├── .github/
│   └── workflows/
│       └── deploy.yml      # Automated GitHub Pages deployment workflow
└── README.md               # This file
```

## 📋 Contents

This repository hosts interactive dashboards produced by the Data Management project, including:

- **Patient-level visualizations** – Gantt charts and timelines for clinical data
- **Summary dashboards** – Aggregated statistics and outcome reports
- **Exploratory analyses** – Plots and figures generated during data exploration

Each dashboard is a standalone HTML file generated with R (using packages such as `plotly`, `ggplot2`, `flexdashboard`, or similar tools), and can be opened directly in any modern web browser.

## 🚀 Deployment

The repository is configured to deploy automatically to **GitHub Pages** on every push to the `main` branch using the workflow defined in `.github/workflows/deploy.yml`.

No build steps are required — all files are static HTML generated externally and committed here.

## ➕ Adding New Dashboards

To add a new dashboard:

1. Generate the HTML output from R (e.g., `rmarkdown::render()` or export from `flexdashboard`).
2. Place the file (and any accompanying asset folders) inside the `dashboards/` directory.
3. Add a link to `index.html` under the appropriate section.
4. Commit and push to `main` — deployment is automatic.

## 🔒 Privacy & Data Policy

All data underlying these dashboards resides exclusively in the private `Data_Management` repository. No raw or identifiable data is stored in this repository. Only aggregated, anonymized, or otherwise safe-to-share visual outputs are published here.

## 🛠️ Technologies

| Tool | Purpose |
|------|---------|
| R | Dashboard generation |
| plotly / ggplot2 | Interactive and static visualizations |
| R Markdown / flexdashboard | HTML report rendering |
| GitHub Pages | Static site hosting |
| GitHub Actions | Automated deployment |

## 📬 Contact

For questions about the underlying data or analyses, please refer to the `Data_Management` project or contact the repository owner.
