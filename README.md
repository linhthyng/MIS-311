MIS 311 - Individual Assignment

Dataset: Shoe Price  
Student: Ngô Thùy Linh  
University: Eastern International University

**1. Data Overview**

The Shoe Price dataset provides a snapshot of footwear pricing across various brands in the retail market. Each entry represents a specific shoe product and includes details regarding product specifications such as brand name, color, size, and the listed retail price.

•	Brand (object): brand name of the product  
•	Color (object): color of the product  
•	Size (float64): size of the product  
•	Price (float64): price of the product

The dataset comprises 202 rows and 4 columns, featuring both categorical variables (Brand, Color) and numerical variables (Size, Price). This combination offers a clear perspective on pricing strategies and product diversity in the footwear market, making the dataset ideal for exploratory data analysis within a business analytics context.

<img width="583" height="127" alt="Screenshot 2026-01-26 145238" src="https://github.com/user-attachments/assets/169e12ab-09c1-4386-886e-44902560ef93" />

<img width="586" height="152" alt="Screenshot 2026-01-26 145259" src="https://github.com/user-attachments/assets/31136b34-ece9-4297-a6b3-ec260f1a2475" />

This dataset was chosen because it illustrates how retailers can use data analytics to uncover pricing patterns, compare brand positioning, and understand the relationship between product attributes (like size or color) and their market value.

**2. Data Cleaning** 

I used Microsoft Excel features, specifically Filter and Remove Duplicates, to inspect the dataset for inconsistencies and ensure data quality.

2.1 Missing Values  
I utilized the Filter function to identify blank cells across all columns.

Price: There was 1 missing value. As Price is the target variable for this analysis, any record lacking this information would distort the financial statistics. Therefore, I also removed the row associated with this missing value.

<img width="577" height="72" alt="Screenshot 2026-01-26 144920" src="https://github.com/user-attachments/assets/aba72b29-1320-49d4-aa7b-beb373804e73" />

Color: There was 1 missing value. Since the color is a key attribute for product categorization and cannot be accurately assumed, I decided to remove the entire row containing this missing value.

<img width="575" height="68" alt="Screenshot 2026-01-26 144805" src="https://github.com/user-attachments/assets/a7bdc0db-9ee4-48eb-adf5-8a2a3338859a" />



  
2.2 Remove Duplicates   
To ensure the uniqueness of the transaction records, I used the Remove Duplicates tool in the Data tab.  
I selected the entire dataset and checked the option "My data has headers". The system identified and removed 3 duplicate rows.

<img width="1851" height="414" alt="Screenshot 2026-01-26 145032" src="https://github.com/user-attachments/assets/ffba109e-53b8-4d2a-b980-869dbf9774a8" />


  
2.3. Cleaning Summary     
Data cleaning was conducted to ensure the dataset’s accuracy, completeness, and consistency before performing any analysis. The original dataset contained 202 rows. After removing 2 rows with missing values and 3 duplicate entries, the final clean dataset consists of 197 rows ready for analysis.

**3. Descriptive Statistics**

3.1 General Price Overview  
The analysis of the cleaned dataset (197 observations) reveals that the average price of a pair of shoes is $212.92. The prices range widely from a minimum of $80 to a maximum of $350.
The standard deviation is 79.27, which is relatively high. This indicates a significant variation in pricing strategies across different brands. The median price ($214) is very close to the mean.

<img width="392" height="540" alt="Screenshot 2026-01-27 112056" src="https://github.com/user-attachments/assets/fdeba58e-7040-49e8-9fad-366303bd146d" />

3.2. Brand Analysis Chart 1  
As illustrated in Chart 1, PUMA commands the highest average price at $307, followed by LaBriza $281 and Umbro $266. This positions them as premium options in this dataset. Conversely, popular global brands like Nike $168 and FILA $161 appear in the lower price tier in this specific dataset, likely due to a focus on entry-level or mass-market product lines.

<img width="767" height="511" alt="Screenshot 2026-01-28 101721" src="https://github.com/user-attachments/assets/0dc74e36-334d-4772-8554-3adc662b796d" />


3.3. Price Distribution Chart 2    
The frequency of products in the $80–$320 range is quite high and evenly distributed ranging from 33 to 38 products per group. This shows that the shoe category mainly targets the middle market, and no specific price is absolutely dominant.The retailer is using a balanced pricing strategy, spreading products out to meet different budget levels within the mid-market segment.

<img width="953" height="596" alt="Screenshot 2026-01-28 101658" src="https://github.com/user-attachments/assets/53a75ed3-96a0-41df-a5d2-ddfa52c6b275" />











