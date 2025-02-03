# Car-Sales-Analysis
Car Sales Analysis using QlikView

### Project Overview
The Goal of this analysis is to explore car sales data to identify trends, patterns and insights that can help in making strategic decisons in the automotive industry.
The dataset is provided by Kaggle https://www.kaggle.com/datasets/missionjee/car-sales-report and represents a data collection on the automotive sales industry in USA for the city: Austin,Janesville,Scottsdale,Pasco,Aurora,GreenVille and Middletown. 

Dataset Description:
- **Car_id** : Unique identifier for each car in the dataset.
- **Date** : Date of the car sale transaction.
- **Customer Name** : name of the customer purchasing the car.
- **Gender** : Gender of the customer.
- **Annual Income** : Annual income of the customer.
- **Dealer name** : Name of the car dealer associated with the sales.
- **Company** : Company or brand of the car.
- **Model**: Model name of the car.
- **Engine** : Specifications of the car's engine.
- **Transmission** : Type of transmission in the car.
- **Price** : Listed price of the car for sale.
- **Dealer_No** : Dealer identification number associated with the sale.
- **Body Style** : Style or design of the car's body.
- **Phone** : Contact phone number associated with the car sale.
- **Dealer_Region** : Geographic region or location of the car dealer.
  
Key Analyses to conduct:
1. **Sales Trends** : Identify the best-selling car models and brands over time.
2. **Geographical Analysis**: Analyze differences in sales based on location.
3. **Price vs. Sales Impact**: Study the correlation between price and the number of units sold.
4. **Seasonality Analysis**: Detect sales patterns across different times of the year.
5. **Market Segmentation**: Categorize vehicles based on their characteristics to determine which segments perform best.

#### Data Loading and Preparation
I began by loading the dataset using the script editor. After importing the data, I formatted the date column and extracted additional time-related fields such as Year, Month, Month-Year Name, Quarter, and Weekday to enhance the depth of my analysis.

Additionally, I categorized car prices into four levels: Lower, Lower-Mid, Mid, and High to facilitate segmentation.

#### Dashboard Overview
I created three distinct dashboards:

- **Sales Trend Analysis** – To identify key patterns in car sales over time.
- **Geographical Sales Analysis** – To explore regional variations in sales performance.
- **Customer Insights** – To analyze purchasing behavior based on customer attributes.

#### Key Insights from the Sales Trend Dashboard

![image](https://github.com/user-attachments/assets/815cd8fc-67e9-405c-a767-cff0bf6ea059)

- Sales improved in 2023 compared to 2022, with November and December being the peak months for both years. In contrast, January experienced a significant drop in sales.
- The car market is highly competitive, with no single brand dominating. However, Chevrolet leads in both total sales and units sold, followed by Ford and Dodge (all American brands).
-The best-selling car model is the Lexus LS400, despite Lexus not ranking in the overall top 10 brands. It is followed by Volkswagen Jetta and Oldsmobile Silhouette.

#### Key Insights from the Geographical Sales Dashboard

![image](https://github.com/user-attachments/assets/2bad9c67-ea79-4412-964b-8cc55312ad23)

- Austin recorded the highest number of transactions, while Greenville and Middletown had the lowest sales.
- The top-performing dealer is in Janesville, but overall, sales among the top 10 dealers are highly competitive.
- Sales across all cities are closely competitive. Even Austin, which leads in sales, holds a market share of 17.45%, while the lowest (Middletown) still maintains a 12.98% market share.

#### Key Insights from the Customer Analysis Dashboard

![image](https://github.com/user-attachments/assets/053a6a9d-d174-401a-a77c-7aadfad998c1)

- The dataset contains more male than female buyers.
- Both genders primarily prefer Pale White cars with automatic transmissions and hatchback body styles.
- The majority of cars sold belong to the Lower-Mid price range.
- The scatter plot shows a positive correlation between annual income and car price, indicating that higher earners tend to buy more expensive models. Some brands, like Ford and Nissan, dominate the lower-income range, while luxury brands such as Porsche and Mercedes are favored by high earners. Brands like Toyota and BMW span a wide price range, offering both affordable and premium models





   

