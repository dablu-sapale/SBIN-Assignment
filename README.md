# ASSIGNMENT

## Question :
1) We have SBI stock Open, high, low, close and volume data for every minute for every day

2) The data is from 1st Jan 2024 till 31st Jan 2024

(Each day having 375 rows of data i.e. 915 am till 329 pm)

3) We have to rank the volume in a such a way that it checks the exact same time for every day and for the last 5 days, it gives us the rank of volume (rank 1 means highest volume)

 *Certainly! Assignment involves analyzing SBI (State Bank of India) stock data for the month of January 2024.*

1. **Data Description**: You are provided with minute-level data for each trading day in January 2024. The data includes the following attributes for SBI stock:
   - Open price
   - High price
   - Low price
   - Close price
   - Volume traded

2. **Task**: Task is to rank the volume of SBI stock traded at a specific time for each day over the last 5 days.

3. **Objective**: The objective is to determine the relative volume ranking at a specific minute of the trading day, considering the same minute for the past 5 trading days. A rank of 1 indicates the highest volume at that minute over the past 5 days.

4. **Approach**: You need to develop a solution that systematically compares the volume at a specific minute across the last 5 trading days and assigns a rank based on the volume comparison. This involves iterating through the data for each day, identifying the volume at the specified minute, and comparing it with the volumes at the same minute over the past 5 days.

5. **Output**: The output of your solution should be the volume rank at the specified minute for each trading day in January 2024.

Overall, the assignment tests your ability to analyze time-series data, perform comparative analysis across multiple days, and derive meaningful insights from stock market data.
