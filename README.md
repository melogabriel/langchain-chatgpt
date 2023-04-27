## LangChain + ChatGPT for Data Analysis

This is a code that uses the LangChain library and OpenAI's ChatGPT API to perform data analysis on a dataset.

## Requirements

To run this code, you will need the following requirements:

- An OpenAI platform account and an API key: You can create an account and obtain an API key by following the instructions on the [OpenAI website](https://beta.openai.com/docs/api-reference/authentication). Once you have an API key, you will need to add it to the .env file in this repository. To do this, simply create a new line in the file with the following format: OPENAI_API_KEY=<your-api-key> and replace <your-api-key> with your actual API key. Save the file after adding your key.
- A CSV file with the data you want to analyze

Before running the code, you need to fill in the OpenAI API key in the .env file. After that, simply run the langchain_chatgpt.py file to run the code.

## The code will perform the following tasks with the added sample dataset 'perfumes.csv':

- Identify the product category with the highest revenue, the revenue value, and the best-selling product in the category.
- Calculate the total revenue for each category and save it in an Excel file named "revenue_summary.xlsx" on the computer.
- Generate a bar chart with revenue in millions per category of the top 8 categories.
- Create a new Excel file named "analise_perfumes.xlsx" and add a tab named "revenue_by_year_month". Then, read the added dataframe containing product revenue information. In the "revenue_by_year_month" tab, aggregate the columns "Year", "Month of the year", and "Product Revenue" for each "Month of The Year". Finally, save the Excel file as "analise_perfumes.xlsx" on the computer.
- Generate a chart with revenue by year-month.

