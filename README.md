# vehicle-sales-dashboard-powerbi
An interactive Power BI dashboard analyzing vehicle sales across major automobile brands in India — featuring segment-wise breakdown, model comparisons, fuel type filters, brand logo slicers, and dynamic car images. Built with Power BI, DAX, and Excel data source (VD.xlsx).

An interactive Power BI dashboard analyzing vehicle sales across major automobile brands in India. The dashboard provides insights into monthly sales performance, segment-wise distribution, model variants, and price range — all filterable in real time.

---

## 📸 Dashboard Preview

![Vehicle Sales Dashboard](dashboard_preview.png)

---

## 📊 Dashboard Overview

The dashboard is built on a single-page layout with a clean, modern dark-blue theme and includes brand logos and car images for a polished visual experience.

### 🔢 KPI Cards
| Metric | Value (Sample) |
|---|---|
| Total Monthly Sales (Units) | 7M |
| Price Range (Ex-Showroom, ₹ Lakhs) | 10.00 – 30.00 |

### 📈 Visuals Included

| Visual Type | Title | Description |
|---|---|---|
| **Donut Chart** | Sum of Monthly Sales (Units) by Segment | Breakdown of sales across Hatchback, Compact SUV, Sedan, SUV, and MPV segments |
| **Clustered Column Chart** | Total Monthly Sales by Model | Compares monthly unit sales across car models (e.g., Kicks vs Magnite) |
| **Bar Chart** | Total Variants by Model | Shows the number of variants available per car model |
| **Card** | Total Monthly Sales | Aggregate sales units KPI |
| **Card** | Price Range (₹ Lakhs) | Min–Max Ex-Showroom price |
| **Image Slicer** | Brand Logo Selector | Clickable brand logos (BMW, Renault, Maruti Suzuki, Jeep, Nissan, Toyota, BYD, etc.) for filtering |
| **Car Image Panel** | Selected Car Visual | Displays a photo of the selected car model |
| **Slicer** | Fuel Type | Filter by Diesel, Electric, Petrol, Petrol/CNG |
| **Slicer** | Segment | Filter by Compact SUV, Electric Hatchback, Electric SUV, etc. |
| **Slicer** | Launch Year | Range slider from 2015 to 2023 |

---

## 🗂️ Data Model

The dashboard uses two data tables:

### Sheet1 — Vehicle Sales Data
| Column | Description |
|---|---|
| Model | Car model name |
| Fuel Type | Diesel / Petrol / Electric / Petrol-CNG |
| Segment | Hatchback / Sedan / SUV / Compact SUV / MPV |
| Launch Year | Year the model was launched |
| Monthly Sales (Units) | Number of units sold per month |
| Ex-Showroom Price (₹ Lakhs) | Price of the vehicle |
| Variants | Number of variants available |

### Sheet2 — Brand Image Data
| Column | Description |
|---|---|
| CAR | Car/Brand name |
| URL | Image URL used in the brand logo slicer |

---

## ✨ Features

- **Interactive Brand Slicer** — Click on any brand logo (BMW, Nissan, Toyota, Maruti Suzuki, Jeep, Renault, BYD, etc.) to filter all visuals for that brand
- **Dynamic Car Image** — Dashboard displays a real photo of the selected car model
- **Multi-filter Support** — Combine Fuel Type, Segment, and Launch Year slicers simultaneously
- **Segment Sales Breakdown** — Donut chart with percentage labels for quick segment comparison
- **Model-level Drill Down** — Column and bar charts show per-model performance
- **Clean Dark Theme** — Professional dark blue background with white text for readability

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard development |
| **Microsoft Excel / CSV** | Source data (Sheet1 & Sheet2) |
| **Power Query** | Data transformation & loading |
| **DAX** | Calculated measures (Sum, Min) |
| **Image URLs** | Brand logos and car photos embedded via slicer |

---

## 📁 Repository Structure

```
vehicle-sales-dashboard-powerbi/
│
├── vehicle.pbix            # Main Power BI dashboard file
├── VD.xlsx                 # Source data (Sheet1: Sales Data, Sheet2: Brand Images)
├── README.md               # Project documentation
└── dashboard_preview.png   # Screenshot of the dashboard
```

> **Note:** The `.pbix` file includes embedded images (brand logos and car photos). No external image files are needed — they are loaded via URLs in the data model.

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `vehicle.pbix` in Power BI Desktop
4. Interact with the slicers and visuals to explore the data

```bash
git clone https://github.com/your-username/vehicle-sales-dashboard.git
cd vehicle-sales-dashboard
# Open vehicle.pbix in Power BI Desktop
```

---

## 🔍 How to Use the Dashboard

1. **Select a Brand** — Click a brand logo from the top image slicer to filter by manufacturer
2. **Filter by Fuel Type** — Use the left-side slicer to view Diesel, Electric, Petrol, or Petrol/CNG vehicles
3. **Filter by Segment** — Narrow down to Compact SUV, Hatchback, Sedan, SUV, MPV, etc.
4. **Adjust Launch Year** — Drag the range slider to focus on vehicles launched in specific years
5. **Read the KPIs** — Cards update dynamically to show filtered Total Sales and Price Range
6. **Explore Charts** — Column, Bar, and Donut charts all respond to active filter selections

---

## 📌 Key Insights (Sample)

- **Compact SUV** is the top-selling segment, contributing ~43.78% of total monthly sales
- **SUV** is the second largest at ~26.82%, followed by **Hatchback** at ~16.25%
- **Nissan Kicks & Magnite** are among the highlighted models with high variant counts
- Price range spans **₹10 – ₹30 Lakhs**, covering budget to mid-range segments
- The dashboard covers brands including **BMW, Renault, Maruti Suzuki, Jeep, Nissan, Toyota, and BYD**

---

## 📄 License

This project is for educational and portfolio purposes. Data used is for demonstration only.

---

## 🙋‍♂️ Author

**Chinmay Gawde**
- GitHub: https://github.com/gawdechinmay17
- LinkedIn: https://www.linkedin.com/in/chinmay-gawde-060339200/

---

*Built with ❤️ using Power BI*
