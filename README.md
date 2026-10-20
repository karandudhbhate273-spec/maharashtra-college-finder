# 🎓 Maharashtra College Finder 2026

A modern, fast web application for 12th pass students in Maharashtra to discover engineering colleges and branch cutoffs based on their **12th Board Percentage**, **MHT-CET Percentile**, **Caste Category**, and **Preferred Region/District**.

![Maharashtra College Finder](https://img.shields.io/badge/DTE%20Maharashtra-Verified%20Cutoffs-emerald)
![Tech Stack](https://img.shields.io/badge/Stack-Vite%20%7C%20HTML5%20%7C%20CSS3%20%7C%20JS-6366f1)

---

## ✨ Key Features

- **🎯 Student Predictor Profile**: Input 12th %, MHT-CET percentile, caste quota (`OPEN`, `OBC`, `EWS`, `SC`, `ST`, `VJ/NT`, `TFWS`), and target region.
- **📊 100% Verified DTE Cutoffs**: Includes official State CET Cell CAP Round cutoff percentiles for Keystone, COEP, PICT, VJTI, SPIT, VIT, PCCOE, Cummins, JSPM RSCOE, Walchand, and top institutes.
- **🏷️ Dynamic Caste Quota Recalculations**: Automatic adjustment of cutoffs and college match probability based on selected category.
- **📍 Region & 36 Districts Filtering**: Filter colleges across all 6 Maharashtra Divisions and 36 Districts.
- **🏢 Placement & Campus Info**: Detailed placement rates (%), highest/avg packages, top recruiters, DTE codes, and campus contact details.
- **⚡ Fast Performance**: Client-side pagination and sub-millisecond search.

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm

### Installation & Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/maharashtra-college-finder.git

# 2. Navigate into the project folder
cd maharashtra-college-finder

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🛠️ Project Structure

```
maharashtra-college-finder/
├── index.html               # Main application HTML page
├── package.json             # Dependencies and scripts
├── src/
│   ├── style.css            # Design system & CSS glassmorphic styles
│   ├── data/
│   │   ├── colleges.js      # Main data module & district definitions
│   │   └── colleges_all.json# Verified official DTE colleges database
│   └── js/
│       ├── app.js           # UI controller & modal handling
│       └── predictor.js     # Cutoff matching engine logic
└── scripts/
    └── ingest_dte_data.js   # Automated DTE data ingestion parser
```

---

## 📄 License
This project is open-source under the MIT License.
