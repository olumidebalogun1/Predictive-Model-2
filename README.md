# **Sales Forecasting Using Prophet model**

## **Introduction**
In today’s fast-paced business environment, **timely forecasting is essential** for staying competitive and agile. Among modern forecasting tools, **the Prophet model** stands out for its ability to **accurately predict trends in time series data**, effortlessly handling **seasonality, holidays, and missing values**. I recently applied this powerful technique to **train and deploy my second Python-based predictive model**, forecasting **sales for the next two years**. This project demonstrated the practical strength of Prophet in **turning raw data into reliable, forward-looking insights**, reinforcing its value as a **go-to solution for real-world business forecasting**.

## **Why This Sales Forecasting Project Matters**

1.**Anticipates Future Sales Trends**:

- By forecasting sales 24 months ahead, businesses can proactively plan instead of reacting blindly. 

2. **Data-Driven Decision-Making**:

- The Prophet model equips decision-makers with solid projections to support strategic moves, such as budgeting, staffing, and inventory management. 

3. **Optimizes Inventory Management**:

-  Avoids understocking and overstocking by aligning supply with forecasted demand, reducing waste and lost revenue. 

4. **Enhances Financial Planning**:

- Monthly revenue predictions help in accurate cash flow forecasting, enabling better financial discipline and capital allocation.
   
S. **Easy to Use, Hard to Mess Up**:

- Prophet is robust and beginner-friendly, meaning analysts can create powerful forecasts without needing to build custom models from scratch. 


## **Files**
-	 [Dataset](https://github.com/olumidebalogun1/Predictive-Model-2/blob/main/1.%20Monthly%20Sales%20Dataset.ipynb): The dataset used for this analysis is fictional (synthetically generated) but designed to reflect realistic sales data.

-	[Load and Clean_data](https://github.com/olumidebalogun1/Predictive-Model-2/blob/main/2.%20Load%20and%20Clean.ipynb): This is the code I used to extract and clean the data before loading it into the model.

- [Code](https://github.com/olumidebalogun1/Predictive-Model-2/blob/main/3.%20Predictive%20Model%20Using%20Prophet.ipynb): The full code covers everything from loading and cleaning the dataset to training the model.



## **I. Key Business Question**

### **What will our monthly sales look like over the next two years, based on historical purchasing patterns**?

## **II. Project Overview**

### **1. Business Challenge**:
The company needs to plan for inventory, staffing, and resource allocation. However, it's difficult to make informed decisions without clear visibility into future sales patterns. The challenge is the lack of reliable forecasting tools to anticipate future monthly sales based on historical purchasing behavior.

### **2. Project Goal**:
To develop a robust, data-driven forecasting model using Prophet that predicts monthly sales for the next 24 months. This will support strategic planning and decision-making across operations, finance, and supply chain departments.


## **III. Approach**:

-	**Data Cleaning**: Clean and standardize the dataset to remove errors, ensure consistency, and establish a reliable foundation for accurate analysis.

-	**Feature Expansion**: Enrich the dataset by adding supplementary columns that provide additional context and enhance the depth of analysis.

-	**Data Aggregation**: Resample historical order-level data into monthly sales totals to identify trends and seasonality.

- **Modeling**: Apply Facebook’s Prophet time series model, which is well-suited for business data with strong seasonality and holiday effects.

- **Forecasting**: Extend the time horizon by 24 months and generate forecasts with uncertainty intervals.

- **Visualization**: Combine observed and predicted values in a clear visual format to aid stakeholders in understanding future projections.

- **Deliverables**: Provide a forecast table with upper and lower bounds for monthly sales, along with visual insights.


## **Visual Output: Sales Forecasting Using Prophet Model**
![Sales Forecasting Using Using Prophet Model](https://github.com/user-attachments/assets/9071b53a-aa18-4a3f-a574-ea23b66b56ab)




## **Key Trends and Insights**

### **Consistent Upward Sales Growth**: 
-	Sales are projected to **increase steadily** over the 2-year period:

-	**Feb 2025**: ~$3.33M

-	**Dec 2026**: ~$4.25M


This reflects positive momentum and a strong growth trajectory in monthly revenue.

### **Strategic Recommendations**
1. ### **Revenue Growth Planning**: 
- Use this forecast to set realistic sales targets, budgets, and hiring plans.

2. ### **Inventory and Supply Chain Optimization**: 
- Optimize procurement cycles to match forecasted demand and avoid overstocking while preparing for continued growth.

3. ### **Marketing Budget Scaling**: 
- Allocate more budget toward digital campaigns, especially if growth correlates with past marketing efforts. Consider seasonal boosts if the actual sales historically peak during certain months.
4. ### **Regular Forecast Validation**:
-  Adjust for economic or market changes.

