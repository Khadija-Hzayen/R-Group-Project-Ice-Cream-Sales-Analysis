### 🔧 Key Steps in the Script

#### Load & Explore Data
* Read the CSV file
* View dataset structure
* Preview the first rows

#### Data Preprocessing
* Convert DATE column to Date type
* Rename sales column to: `monthly_units_sold`
* Round sales values
* Check for missing values

#### Exploratory Analysis
* Histogram of monthly sales
* Total yearly sales calculation

#### Data Structures in R
* Vector of month names
* List combining months & sales
* Data frame created from list elements

#### Accessing Data
* Get monthly sales by month name
* Access list and data frame elements

#### Control Structures
* for-loop to print monthly sales
* if-else to compare sales to average

#### Visualization
* Bar plot showing sales per month using:
  ```R
  barplot(sales_data$MonthlySales, names.arg = sales_data$Month, main = "Total Sales for Each Month", xlab = "Month", ylab = "Total Sales (Units)", col = "skyblue", las = 2)
  ### 📈 Outputs

* ✔ Cleaned dataset
* ✔ Histogram of monthly ice cream sales
* ✔ Bar plot comparing monthly sales
* ✔ Summary statistics
* ✔ Sales comparisons relative to average

---

### 🛠 Technologies Used

* R Language
* Base R functions
* Basic visualization (`hist`, `barplot`)

---

### 📌 How to Run

1. Install R
2. Place `ice_cream_sales.csv` in your working directory
3. Run the provided `.R` script
4. View outputs in the R console and plot window
