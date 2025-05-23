# 🏨 Hotel Data Visualization Project

<div align="center">

![Hotel Visualization](https://img.shields.io/badge/D3.js-Visualization-orange)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

An interactive data visualization dashboard analyzing hotel booking patterns, cancellations, and guest demographics.

📌 **[Live Demo](https://mridho24.github.io/visdat/)**

</div>

---

## 📊 Key Visualizations

![Dashboard Preview](images/dashboard.png)

<div align="center">
<img src="preview.gif" alt="Visualization Preview" width="600px"/>
</div>

### 1. 📈 Booking Analysis

- **Cancellations**: Interactive pie & bar charts
- **Monthly Trends**: Time-series visualization
- **Room Types**: Distribution analysis
- **Market Segments**: Customer segmentation
- **Guest Origins**: Geographic distribution
- **Hotel Comparisons**: Performance metrics

## 📊 Dataset & Analysis

### Dataset

- **Name**: Hotel Booking Demand
- **Source**: [Kaggle Dataset](https://www.kaggle.com/jessemostipak/hotel-booking-demand)
- **Size**: 119,390 records
- **Period**: 2015-2017
- **Features**: 32 columns including booking details, guest information, and hotel data

### Jupyter Notebooks

Located in `notebook/` directory:

- `preprocess.ipynb`: Data cleaning and preparation
- `hotel_booking_visualization.ipynb`: Exploratory data analysis

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/mridho24/visdat.git

# Navigate to project
cd visdat

# Start local server (Python 3)
python -m http.server 8000

# Open in browser
http://localhost:8000
```

## 📁 Project Structure

```bash
visdat/
├── 📄 index.html                    # Main dashboard
├── 📊 Pembatalan-Pemesanan.html     # Cancellation analysis
├── 📈 PemesananPerBulan.html        # Monthly trends
├── 🏠 TipeKamar.html                # Room types
├── 👥 Segmen-Pasar.html             # Market segments
├── 🌍 Negara-AsalTamu.html          # Guest origins
├── 🏨 Perbandingan-Jenis-Hotel.html # Hotel comparison
├── 📊 data/                         # Data files
│   └── hotel_bookings_processed.csv # Processed dataset
├── 📓 notebook/                     # Jupyter notebooks
│   ├── preprocess.ipynb            # Data preprocessing
│   └── hotel_booking_visualization.ipynb # Analysis
├── 📸 images/                        # Image assets
│   ├── dashboard.png                # Main dashboard preview
│   └── preview.gif                  # Animation preview
├── 🎨 styles/
│   └── main.css                     # Global styles
└── 📝 README.md                     # Documentation
```

## ✨ Features

<table>
  <tr>
    <td>🎯 Interactive Charts</td>
    <td>📱 Responsive Design</td>
    <td>🔄 Real-time Updates</td>
  </tr>
  <tr>
    <td>💡 Insights Cards</td>
    <td>🎨 Custom Animations</td>
    <td>🔍 Advanced Filtering</td>
  </tr>
  <tr>
    <td>📊 Data Export</td>
    <td>🌈 Dynamic Theming</td>
    <td>⚡ Fast Performance</td>
  </tr>
</table>

## 🛠️ Technologies

- ![D3.js](https://img.shields.io/badge/D3.js-v7-orange)
- ![HTML5](https://img.shields.io/badge/HTML5-Latest-red)
- ![CSS3](https://img.shields.io/badge/CSS3-Latest-blue)
- ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

## 🌐 Browser Support

| <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" /><br>Chrome | <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" /><br>Firefox | <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" /><br>Safari | <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="Edge" width="24px" height="24px" /><br>Edge |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Latest ✔                                                                                                                                                 | Latest ✔                                                                                                                                                     | Latest ✔                                                                                                                                                 | Latest ✔                                                                                                                                         |

## 🌐 Access

- **Live Demo**: [https://mridho24.github.io/visdat/](https://mridho24.github.io/visdat/)
- **Repository**: [https://github.com/mridho24/visdat](https://github.com/mridho24/visdat)
- **Documentation**: Available in notebook comments and README

## 🤝 Contributing

```

1. Fork repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request
```

---

<div align="center">

Made with ❤️ by [Kelompok 10](https://github.com/mridho24)

</div>
