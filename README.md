# Exploratory Data Analysis (EDA) on Hotel Bookings

This repository contains a comprehensive Exploratory Data Analysis (EDA) performed on a dataset of hotel bookings. The analysis aims to uncover trends, patterns, and insights to help hotel management optimize operations and revenue.

---

## Features of the Project

### 1. **Dataset Overview**
The dataset contains information about hotel bookings, including:
- **Hotel Type**: City or Resort Hotel
- **Booking Details**: Lead time, stay duration, ADR (Average Daily Rate), etc.
- **Guest Information**: Number of adults, children, and babies
- **Booking Modifications**: Cancellation status, special requests, and deposit type
- **Market Insights**: Distribution channels and customer segments

---

### 2. **Analyses Conducted**

#### **A. Univariate Analysis**
- Distribution of key variables (e.g., hotel types, cancellation rates, lead time).
- Identification of outliers and dominant patterns.

#### **B. Bivariate Analysis**
- Relationships between numerical and categorical variables:
  - Hotel type vs. cancellation rate
  - Market segment vs. ADR
  - Lead time vs. ADR

#### **C. Multivariate Analysis**
- Interaction between multiple variables:
  - Market segment, hotel type, and ADR
  - Lead time, cancellation status, and ADR
  - Total guests, ADR, and hotel type

#### **D. Correlation Heatmap**
- Examined relationships among numerical variables to identify significant correlations.

#### **E. Pairplot of Selected Features**
- Visualized pairwise relationships for features like lead time, ADR, and special requests.

---

### 3. **Insights Gained**
- City hotels experience higher cancellation rates compared to resort hotels.
- Bookings with longer lead times are more prone to cancellation.
- Special requests are negatively correlated with cancellations, indicating personalization reduces risk.
- Non-refundable deposits significantly reduce cancellation rates.

---

### 4. **Business Recommendations**
- **Cancellation Policies**: Implement stricter policies or incentives for non-refundable bookings.
- **Marketing Strategies**: Focus on high-ADR market segments and last-minute premium pricing.
- **Operational Improvements**: Use insights on lead times and special requests to optimize resource planning.

---

## Repository Structure
- **EDA on Hotel Bookings.ipynb**: Jupyter Notebook containing the full analysis and visualizations.
- **Dataset**: (Not included due to confidentiality; replace with your data source).
- **README.md**: Overview and insights from the project (this file).

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/singhraj827/eda-hotel-bookings.gi
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "EDA on Hotel Bookings.ipynb"
   ```
3. Ensure required libraries are installed (listed below).

---

## Requirements
Install the necessary Python libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

---

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for additional features or improvements.

---

## Contact
For questions or collaborations, please reach out at er.abhisingh827@gmail.com

