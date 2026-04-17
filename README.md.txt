Perfume Data Analysis Project

1. Problem and User
a, This project analyzes ratings of popular perfumes across different brands, genders, and main notes.
b, The goal is to help consumers make better choices when purchasing perfumes based on data.

2. Data Source
a, Source: Manually collected from public perfume information (official website platform).
b, Data size: 25 perfumes.
c, Key fields: Brand, Perfume, Gender, Rating, Price (USD), Volume (ml), Main Note.

3. Methods to analyze
Using Python (pandas, matplotlib) to:
a, Clean and prepare data, check and convert data types.
b, Group data by brands, genders and notes.
c, Calculate average ratings.
d, Visualize findings with bar charts and scatter plots.

4. Key Findings
a. "Citrus"notes have the highest average rating (4.60/5.00), "Aquatic"notes have the lowest average rating (4.25/5.00).
b. Male perfumes score slightly higher (4.47/5.00) than female (4.38/5.00).
c ."Creed, Chanel, and Dior"are the top-rated brands.
d. Price and rating have no clear correlation, which indicates that expensive perfumes doesn't mean better.

5. How to Run
a. Install Python and Jupyter Notebook.
b. Install dependencies:"pip install pandas matplotlib".
c. Open"perfume_analysis.ipynb"and run all cells.

6. Limitations and Next Steps
a, The dataset is small (only 25 perfumes), later the dataset can expand to more brands and types.
b, Perfume is a relatively personalized product. However, the dataset is more popular and cannot meet the need of a small number of users.
c, I can build a recommendation system in the future.

7. AI Disclosure
This project used ChatGPT/DeepSeek for:
a, Code debugging and error fixing.
b, README structure guidance.
c, Data analysis suggestions.