# 🧫 Belly Button Biodiversity Dashboard

## 🧬 Overview

This interactive data visualization dashboard explores the biodiversity of bacterial species in the human belly button. The data originates from a study of microbial species found in volunteer samples. Using **D3.js** and **Plotly.js**, the dashboard allows users to examine microbial prevalence across different individuals.

---

## 🔧 Tools & Technologies

- JavaScript
- D3.js
- Plotly.js
- HTML/CSS

---

## 📁 Project Structure

```
belly-button-challenge/
├── index.html              # Main HTML file
├── static/
│   ├── js/
│   │   └── app.js         # JS logic for fetching and plotting
├── samples.json            # Dataset used for all plots
└── README.md               # Project documentation
```

---

## 📊 Dashboard Features

1. **Dropdown Menu**
   - Select any individual sample ID

2. **Bar Chart**
   - Top 10 OTUs (Operational Taxonomic Units) per individual
   - Uses `sample_values`, `otu_ids`, and `otu_labels`

3. **Bubble Chart**
   - All OTUs for selected individual
   - Marker size and color represent abundance and ID

4. **Demographics Panel**
   - Displays key metadata (age, gender, location, etc.) for selected sample

5. **Dynamic Interactivity**
   - All plots and metadata update on dropdown change

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/Geo222222/belly-button-challenge.git
cd belly-button-challenge
```

2. Open `index.html` in your browser. No server required.

> Make sure `samples.json` is accessible via relative path or hosted externally if deploying.

---

## 🌐 Deployment

You can deploy this dashboard using GitHub Pages or any static hosting provider.

---

## 📌 Future Enhancements

- Add filter controls by demographic or OTU category
- Visualize additional statistical insights (mean, median, diversity index)
- Make the dashboard responsive across devices

---

**Author:** [Geo222222](https://github.com/Geo222222)  
**Focus:** Data Visualization • Microbial Analytics • JavaScript Development

