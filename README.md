# 🚍 CMU Bus GPS Analysis Dashboard

## 📊 Project Overview
An interactive web dashboard for analyzing GPS tracking data from CMU buses, identifying signal loss patterns, and visualizing route information on an interactive map.

**Live Demo:** [Add your deployment URL here]

## ✨ Features
- 📍 Interactive map with GPS loss locations
- 📈 Comprehensive data analysis and statistics
- 🗺️ Google Maps integration for route verification
- 📊 Data quality metrics and insights
- 🎨 Modern, responsive UI with Tailwind CSS

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Tailwind), JavaScript
- **Maps:** Leaflet.js + OpenStreetMap
- **Data Analysis:** Python (Pandas, NumPy)
- **Data Visualization:** Chart.js, Plotly

## 📁 Project Structure
```
cmu_cursor_Pty2/
├── index.html              # Main dashboard
├── *.csv                   # GPS data files
├── *.py                    # Python analysis scripts
├── requirements.txt        # Python dependencies
└── README_TH.md           # Thai documentation
```

## 🚀 Quick Start

### Option 1: View Locally
Simply open `index.html` in a modern web browser.

### Option 2: Deploy Online
This is a static website that can be deployed to:
- **GitHub Pages** (Free)
- **Netlify** (Free - Drag & Drop)
- **Vercel** (Free - Fast CDN)
- **Cloudflare Pages** (Free)

## 📦 Python Scripts (Optional)
For data analysis and processing:

```bash
# Install dependencies
pip install -r requirements.txt

# Run analysis scripts
python analyze_bus_gps.py
python clean_gps_data.py
python visualize_gps.py
python google_maps_integration.py
```

## 📊 Data Files
- `bus_gps_problems.csv` - Identified GPS issues
- `gps_loss_locations.csv` - GPS signal loss coordinates
- `purple_bus.csv` - Purple bus route data
- `route_gps_problems.csv` - Route-specific problems

## 🎯 Key Insights
The dashboard provides analysis on:
- Missing data patterns (getoff, pressure, temp1, temp2 columns)
- GPS accuracy variations
- Speed and passenger data distribution
- Route-specific issues
- Temporal patterns in data collection

## 📱 Browser Support
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## 📄 License
Educational project - Chiang Mai University

## 👥 Contributors
- [Add your name/team here]

## 📮 Contact
For questions or feedback, please contact [your email/contact]

---

**Note:** This dashboard is built for educational and research purposes to analyze and improve CMU's bus tracking system.

