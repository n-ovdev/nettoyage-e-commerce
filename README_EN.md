# 🛒 E-commerce Data Cleaning Project

## 📋 Description

E-commerce data analysis and cleaning project created as part of my Data Analyst portfolio. This project demonstrates my skills in data manipulation using Python and Pandas.

## 🎯 Objectives

- Clean an e-commerce dataset containing typical errors
- Standardize data formats
- Produce a report with visualizations
- Deliver clean, usable data

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Development environment

## 📊 Issues Identified and Fixed

### Before cleaning (16 rows)
- ✅ 1 duplicate row
- ✅ 3 missing values (customer names, emails)
- ✅ Format inconsistencies (uppercase/lowercase)
- ✅ 1 negative price (data entry error)
- ✅ 1 zero quantity (invalid)
- ✅ Non-standardized product names

### After cleaning (10 rows)
- ✅ Complete and consistent data
- ✅ Standardized formats
- ✅ Valid values only

## 📂 Project Structure
```
ecommerce-project/
│
├── nettoyage_ecommerce.ipynb       # Main notebook
├── ecommerce_sale.csv               # Raw data
├── ecommerce_propre.csv             # Clean data
├── graphique_commandes_produit.png  # Visualization 1
├── graphique_ca_produit.png         # Visualization 2
├── graphique_statut_commandes.png   # Visualization 3
├── graphique_distribution_prix.png  # Visualization 4
└── README.md                        # Documentation
```

## 🚀 Installation and Usage

### Prerequisites
```bash
pip install pandas matplotlib jupyter
```

### Execution
```bash
jupyter notebook nettoyage_ecommerce.ipynb
```

## 📈 Key Results

- **Cleaning rate**: 37.5% problematic data removed
- **Total sales amount**: [Your amount] €
- **Best-selling product**: Laptop
- **Main status**: Delivered

## 📊 Visualizations

### 1. Orders by Product
![Orders by product](graphique_commandes_produit.png)

### 2. Revenue by Product
![Revenue by product](graphique_ca_produit.png)

### 3. Order Status Distribution
![Status distribution](graphique_statut_commandes.png)

### 4. Price Distribution
![Price distribution](graphique_distribution_prix.png)

## 🎓 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Anomaly detection and correction
- Data cleaning (duplicates, missing values)
- Format standardization
- Data visualization
- Technical documentation

## 📧 Contact

**NOAH TONTOLO**
- LinkedIn: NOAH TONTOLO
- Email: noahtontolo@gmail.com
- Portfolio: ComeUp, Fiver, Malt

## 📝 License

This project is open-source and for educational purposes.

## 🔗 Autres projets

- [Analyse joueurs de football](https://github.com/[ton-username]/analyse-joueurs-football)
