# 🚗 Car Sales Dashboard

An interactive dashboard for analysing a used-car vehicle dataset. It summarises sales by fuel type, year, seller type, transmission, ownership history and top-priced models, so trends in the car market are easy to spot at a glance.

![Car Sales Dashboard](images/dashboard.png)

---

## 📌 Overview

This project turns a raw vehicle dataset into a single-page dashboard with KPI cards and charts. It helps answer questions such as:

- Which fuel type sells the most?
- How have sales changed from 2010 to 2019?
- Who sells more cars: dealers, Trustmark dealers or individuals?
- How much of the market is automatic vs manual?
- Which cars have the highest selling price?

---

## 📊 Dashboard Contents

### KPI Cards

| KPI | Value |
|---|---|
| Total Cars | 5187.9M |
| Average Selling Price (per car) | ₹0.6M |
| Maximum Selling Price (per car) | ₹10.0M |
| Total Sales Price | 5187M |

### Charts

| Chart | What it shows |
|---|---|
| **Sales by Fuel Type** | Cars sold by fuel: Diesel (4,402), Petrol (3,631), CNG (57), LPG (38) |
| **Sales by Year** | Total sales value per year, 2010–2019 (highest in 2019) |
| **Seller Type** | Dealer 53%, Trustmark Dealer 29%, Individual 18% |
| **Gear (Transmission)** | Automatic 80%, Manual 20% |
| **Owners** | Sales value by ownership: First, Second, Third, Fourth & Above, Test Drive Car |
| **Cars** | Maximum selling price by model (Audi, BMW, Mercedes-Benz, Volvo) |

---

## 🔍 Key Insights

- **Diesel and petrol dominate** the dataset, while CNG and LPG are negligible.
- **Dealers account for over half** of all sales; individuals are the smallest seller group.
- **Automatic** cars make up about 80% of the transmission split.
- **Sales value peaks in 2019** and generally declines toward earlier years.
- **Premium models** (Volvo XC90, BMW X7, Audi A6) sit at the top of the price range, reaching about ₹10M.
- **Test Drive Cars** show the highest sales value in the ownership chart.

---

## 🛠️ Tools Used

- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers)
- Data cleaning and transformation
- Dashboard design and formatting

---

## 📁 Repository Structure

```
├── README.md
├── data/
│   └── car_dataset.csv        # vehicle dataset
├── dashboard/
│   └── Car_Sales_Dashboard.xlsx
└── images/
    └── dashboard.png          # dashboard screenshot
```

> Adjust the file names above to match your repository.

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open `dashboard/Car_Sales_Dashboard.xlsx` in Microsoft Excel.
3. Use the slicers and filters (fuel type, transmission, owner, etc.) to explore the data.

---

## 📈 Dataset

The dataset contains vehicle records with fields such as:

- Car name / model
- Year
- Selling price
- Fuel type
- Seller type
- Transmission
- Owner type

---

## 🔮 Future Improvements

- Add filters for brand and price range
- Add a km-driven vs price analysis
- Build a Power BI / Tableau version
- Automate data refresh

---

## 👤 Author

**Your Name**
GitHub: [@your-username](https://github.com/your-username)
LinkedIn: [Your Profile](https://linkedin.com/in/your-profile)

---

⭐ If you found this project useful, please give it a star!

