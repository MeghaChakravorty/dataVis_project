# 📊 dataVis_project

This project is an interactive data visualization application built with **React**, **Chart.js**, and **PapaParse**. It visualizes anime-related data using bar charts, line charts, area charts, and scatterplots. The app is designed to explore trends and patterns in anime datasets interactively.

---

## 🚀 Getting Started

To run the app locally, follow the steps below:

### 🔧 Setup Instructions

```bash
# Step 1: Clone the project
git clone https://github.com/your-username/dataVis_project.git

# Step 2: Navigate to the anime-chart folder
cd dataVis_project/anime-chart

# Step 3: Unzip the data into public folder
unzip viz_data.zip -d ./public/
mv public/viz_data/* public/
rm -r public/viz_data/

# Step 4: Install required dependencies
npm install react-chartjs-2 chart.js papaparse

# Step 5: Start the development server
npm start

# Step 6: Open your browser
http://localhost:3000
```

---

## 📁 Project Structure

```
dataVis_project/
└── anime-chart/
    ├── public/
    ├── src/
    │   ├── components/
    │   │   ├── AnimeBarChart.jsx
    │   │   ├── AnimeLineChart.jsx
    │   │   ├── AnimeAreaChart.jsx
    │   │   ├── AnimeScatterPlot.jsx
    │   │   └── ...
    │   ├── App.jsx
    │   ├── index.js
    │   └── styles/
    └── package.json
```

---

## 📦 Dependencies

```
React
Chart.js
react-chartjs-2
PapaParse
```

---

## 🎯 Features

```
📊 Interactive bar, line, area, and scatter plots
📂 CSV parsing and dynamic updates
⚡ Real-time filtering by country or category
💻 Responsive and modular design
```

---

## 💡 Future Enhancements

```
- Filter by genre, release year, or studio
- Enhance tooltips and transitions
- Add option to upload CSV files
- Export visualizations as images
```
