# Capstone-Project-Advanced-Machine-Learning

### About the Dataset

The dataset provides comprehensive historical sales data, designed to facilitate the analysis and forecasting of retail performance. Below is a detailed overview:

#### General Information
- **Number of Entries:** 421,570  
- **Number of Columns:** 16  
- **Memory Usage:** 48.6+ MB  

#### Column Details:
1. **Store (int64):**  
   - Unique identifier for each store.  
   - Total stores: 45.

2. **Dept (int64):**  
   - Unique identifier for each department within the stores.

3. **Date (datetime64[ns]):**  
   - Weekly date of the recorded data.  
   - Range: 2010-02-05 to 2012-10-26.

4. **Weekly_Sales (float64):**  
   - The weekly sales figure for each department in a store.  
   - Measured in monetary units.

5. **IsHoliday (bool):**  
   - Indicates if the week includes a major holiday (True/False).  
   - Major holidays include Super Bowl, Labor Day, Thanksgiving, and Christmas.

6. **Temperature (float64):**  
   - Average temperature for the store's region during the week, measured in degrees Fahrenheit.

7. **Fuel_Price (float64):**  
   - Cost of fuel in the region during the week.

8. **MarkDown1 to MarkDown5 (float64):**  
   - Anonymized data for promotional markdown events.  
   - These fields capture various types of price reductions.

9. **CPI (float64):**  
   - Consumer Price Index, reflecting the overall change in price levels for goods and services.

10. **Unemployment (float64):**  
    - Unemployment rate in the region.

11. **Type (object):**  
    - Type of store, categorized as 'A', 'B', or 'C'.  
    - Indicates the store's size and characteristics.

12. **Size (int64):**  
    - The square footage of the store.

#### Summary of Data:
- **Date Coverage:** From February 5, 2010, to October 26, 2012.  
- **Holiday Impact:** Holiday weeks are weighted five times higher in evaluation metrics compared to non-holiday weeks.  
- **Missing Values:** None observed, ensuring complete data for analysis.  
- **Categorical Data:** Store type (Type) and holiday indicator (IsHoliday).  
- **Numerical Data:** Includes sales, markdowns, economic indicators, and regional statistics.

This dataset offers a rich blend of sales, promotional, and economic data that is well-suited for advanced analysis, such as demand forecasting, customer segmentation, and market basket analysis.
