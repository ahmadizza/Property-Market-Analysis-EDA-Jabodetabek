# Property-Market-Analysis-EDA-Jabodetabek

## Overview

This project performs an Exploratory Data Analysis (EDA) on residential property listings from five major cities in the Jabodetabek area: Jakarta, Depok, Tangerang, Bogor, and Bekasi. The datasets contain information about property characteristics, pricing, certificate types, location details, and listing metadata.

The analysis focuses on data quality assessment, property market trends, city-level price comparison, and data-driven recommendations for business decisions such as branch expansion and investment opportunities.

---

## Dataset Description

The project uses five datasets: `dfJ`, `dfD`, `dfT`, `dfB`, and `dfX`, each representing properties from Jakarta, Depok, Tangerang, Bogor, and Bekasi.
The datasets include the following variables:

* **Created_at**: Date when the listing was created
* **LT**: Land area (m²)
* **LB**: Building area (m²)
* **KT**: Number of bedrooms
* **KM**: Number of bathrooms
* **Garasi**: Garage capacity
* **Carport**: Carport capacity
* **Lokasi**: Location details
* **Sertifikat**: Type of property certificate
* **Listrik**: Electricity capacity
* **Hadap**: Property orientation
* **Harga**: Listing price in Rupiah
* **URL**: Link to the listing
* **Deskripsi**: Listing description

---

## Data Preprocessing

Several preprocessing steps were conducted, similar to previous projects:

1. Handling duplicate rows
2. Removing unnecessary or unnamed columns
3. Dealing with missing values (over 50% in several variables)
4. Standardizing inconsistent price units (notably in Depok and Tangerang)
5. Cleaning and normalizing categorical variables

---

## Key Insights

### 1. Data Quality Issues

* Numerous unnamed columns across datasets
* High duplication rate
* More than 50% missing values in several variables
* Differences in price units between cities (Depok and Tangerang vs others)

### 2. Recommendations for Data Engineers / DBAs

* Remove unused columns to avoid storage waste
* Implement automated duplicate detection
* Improve data collection pipelines to reduce missing values
* Standardize units, especially for price
* Strengthen data validation at the source

### 3. City Price Comparison

Jakarta has the highest average property price and the largest price variation due to luxury properties and limited land availability. Depok and Bekasi have relatively lower prices, making them more attractive for mid-range buyers.

### 4. Recommended City for New Branch

**Depok** is recommended based on:

* Large number of available listings
* Lower average price compared to other cities
* Strong potential for market growth

### 5. Most Common Property Characteristics

* Bedrooms: 2
* Bathrooms: 2
* Garage: 0
* Carport: 1
* Land area: 60 m²
* Building area: 36 m²
* Certificate: SHM (Hak Milik)
* Price: around Rp 1.2 billion

These indicate a market dominated by small to medium-size family houses.

### 6. Investment Recommendations (Budget: 25 billion)

High-potential properties include:

* Large land plots in Jakarta Pusat with relatively low prices
* High-value properties in Jakarta Selatan and Jakarta Barat
* Affordable options with good long-term potential in Tangerang and Bekasi

The property in Jakarta Pusat shows the highest potential return due to its very large land size.

### 7. Additional Insights

* Bedroom distribution varies by city, with Jakarta having the highest average
* Land area and building area both positively influence price
* Certificate type significantly affects price; SHM + IMB + PBB has the highest average price
* Cities such as Bogor and Tangerang have diverse property sizes and pricing structures

---

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook / Google Colab

---

## Conclusion

The EDA provides valuable insights into the property market landscape in the Jabodetabek region. The analysis highlights data quality issues, city-level market differences, common property characteristics, and strategic recommendations for business expansion and investment decisions.


