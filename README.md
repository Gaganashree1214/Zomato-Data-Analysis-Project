readme_content = """
# Zomato Data Analysis Using Python

## Project Overview
This project analyzes restaurant data to understand patterns in pricing, ratings, and restaurant services.

## Dataset
The dataset contains information about restaurants such as:
- Name
- Online order availability
- Table booking
- Ratings
- Votes
- Approximate cost for two people
- Restaurant type

Total records: 148

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed
- Restaurant type distribution
- Online order availability
- Table booking analysis
- Rating distribution
- Cost distribution
- Cost vs rating relationship
- Votes vs rating analysis
- Correlation heatmap

## Key Insights
1. Dining restaurants dominate the dataset, accounting for over 70% of establishments.

2. Online ordering is available in only 39% of restaurants, showing potential for digital expansion.

3. Table booking services are rare, with only a small percentage offering reservations.

4. Most restaurant ratings fall between 3.5 and 4.2, indicating generally positive customer satisfaction.

5. Average cost for two people is approximately ₹418, suggesting the majority of restaurants are mid-range.

6. Higher cost does not necessarily lead to higher ratings.

7. Restaurants with more customer votes tend to receive better ratings, indicating popularity influences perception.

## Conclusion
This project demonstrates how exploratory data analysis can help understand restaurant trends and customer preferences.
"""

with open("README.md", "w") as f:
    f.write(readme_content)

print("README.md file created successfully!")