# **Stock Market Analysis & Visualization Project**

## **Overview**

This project systematically analyzes historical stock market data for the Indian (Nifty 50\) and U.S. (S\&P 500\) markets, along with currency exchange rates. The primary goal is to extract meaningful insights and visualize complex financial relationships to answer a series of specific questions, focusing on market dynamics, interconnections, and investment strategies.

## **Datasets Used**

The analysis utilizes three primary datasets (assumed to be in CSV format in the project directory):

* SPX.csv: Historical S\&P 500 index data (Date, Open, High, Low, Close, Adj Close, Volume).  
* Final-50-stocks.csv: Historical closing prices for individual Nifty 50 constituent stocks.  
* exchange\_rates.csv: Daily exchange rates for various currencies (including USD and INR via EUR crosses) against the Euro.

## **Key Questions Explored**

The project addresses the following 10 questions, grouped for thematic balance:

**Review 1: Market Interplay & Structural Insights**

1. How did Nifty 50 and S\&P 500 react to major global events like COVID-19?  
2. Can Nifty 50 stocks be clustered as “global-sensitive” vs. “local-insulated” using correlations with USD and S\&P 500?  
3. How do Indian and U.S. markets behave during currency appreciation or depreciation?  
4. The Shifting Pillars of Indian Growth : Tracking Nifty 50's evolving sector growth engines  
5. Is the "Sell in May and Go Away" strategy effective in both India and the U.S.?

**Review 2: Performance Dynamics & Portfolio Strategy**

6. Is there a strong correlation between S\&P 500 and Nifty 50 returns, and how does it change over time?  
7. What are the drawdown and recovery patterns of Nifty 50 vs. S\&P 500?  
8. Can we build a diversified portfolio by identifying low-correlation stocks?  
9. "Nifty 50: Is its growth broad-based or mega-cap concentrated?"  
10. Can we cluster currencies by correlation with USD over time?

## **Visualizations Generated**

For each question, various visualization angles were explored to tell a compelling story:

* **Time-Series Analysis:** Normalized price charts (Area Charts), daily/weekly returns (Bar Charts), Drawdown Analysis (Line Charts), Year-by-Year Performance with Shaded Periods (Line Charts).  
* **Correlation & Clustering:** Scatter Plots (for clustering stocks), Grouped Bar Charts (for average cluster profiles), Violin Plots (for correlation distribution), Market Sync Bubbles (Bubble Chart for annual returns & correlation).  
* **Sector Analysis:** Annual Sector Leaders (Bar Charts), Rolling Performance (Line Charts), Small Multiples Bar Charts (for individual sector annual returns), Pie Chart Timelines (for sector contribution to growth).  
* **Seasonal Analysis:** Dumbbell Plots (for average seasonal returns).

## **Technical Details & How to Run**

This project is implemented in Python and relies on standard data science libraries.

### **Prerequisites**

* Python 3.x  
* pandas  
* numpy  
* matplotlib

* # **seaborn**

* scikit-learn (for KMeans clustering)

You can install these libraries using pip:

pip install pandas numpy matplotlib seaborn scikit-learn

### **Data Files**

Ensure the following CSV files are placed in the **same directory** as your Python script(s):

* SPX.csv  
* Final-50-stocks.csv  
* exchange\_rates.csv

### **Running the Code**

The project's analysis is structured into individual Python code blocks (as provided in the conversation). To run the analysis and generate the visualizations for a specific question:

1. Copy the relevant Python code block (e.g., for Question 1, or Question 4, etc.) into a .py file (e.g., analysis\_q1.py).  
2. Navigate to the directory containing your script and data files in your terminal or command prompt.  
3. Run the script:  
   python analysis\_q1.py

   (Replace analysis\_q1.py with your script's filename).

The script will execute, print any relevant messages to the console, and save the generated plots as PNG image files in the same directory.

## **Learning Outcomes**

This project served as a comprehensive exercise in data visualization and analysis, highlighting:

* **Iterative Design:** The importance of refining visualizations based on feedback to tell a clear story.  
* **Data Preprocessing:** Mastering data cleaning, transformation, and aggregation with pandas.  
* **Chart Selection:** Strategically choosing appropriate chart types (e.g., dumbbell, violin, small multiples) to convey specific insights.  
* **Aesthetic Enhancement:** Leveraging matplotlib and seaborn for visually appealing and readable plots.  
* **Problem Solving:** Debugging and ensuring code robustness in handling real-world data complexities.
