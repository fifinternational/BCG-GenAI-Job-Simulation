# Task Instructions: Analyzing Financial Data from 10-K Filings

## Your Task
Welcome to the BCG C Virtual Internship! As part of the GenAI consulting team, your primary task is to extract and analyze key financial data from the 10-K filings of Microsoft, Tesla, and Apple. This data will be used to develop insights for an AI-powered financial chatbot.

## Step 1: Data Extraction

### Manual Extraction Process
1. Navigate to the SEC's EDGAR database for each company:
   - [Microsoft](https://www.sec.gov/edgar/searchedgar/companysearch.html)
   - [Tesla](https://www.sec.gov/edgar/searchedgar/companysearch.html)
   - [Apple](https://www.sec.gov/edgar/searchedgar/companysearch.html)
   
2. For each company, find the 10-K filings for the last three fiscal years.
3. Extract the following financial figures from each filing: Total Revenue, Net Income, Total Assets, Total Liabilities, and Cash Flow from Operating Activities.
4. Organize Your Data:
   - Compile the extracted data into an Excel spreadsheet for easy reference during your Python analysis.

## Step 2: Preparing Your Jupyter Notebook Environment

### Installation and Setup
1. Install Jupyter (if not already installed):

2. Launch Jupyter Notebook:
This command should open Jupyter in your web browser.

3. Create a new notebook:
- In the Jupyter interface, create a new notebook for your analysis.

## Step 3: Python Analysis in Jupyter

### Data Analysis with Pandas
1. Import pandas:

2. Load your data:
- Convert your Excel file to a CSV file for easier handling, then load it into a DataFrame.

3. Analyzing trends with pandas:
- Use pandas to calculate year-over-year changes for each financial metric. Example:

4. Summarizing findings:
- Conclude your analysis by summarizing your findings directly in the notebook. Use markdown cells to add narrative explanations of your analysis, discussing the trends and changes in financial metrics you've identified.

## Step 4: Documentation and Submission

### Final Steps
1. Document your analysis:
- Use the markdown feature in Jupyter Notebook to document your methodology, observations, and conclusions throughout the notebook.

2. Export your notebook:
- Once your analysis is complete, export your Jupyter Notebook as a PDF or HTML file for submission.
- You can do this from the "File" menu in Jupyter, selecting "Download as" and then choosing your preferred format.

This approach allows you to focus on the core analytical aspects using pandas within a Jupyter Notebook, providing a clear, documented narrative of your financial analysis process. By the end of this task, you'll have a comprehensive understanding of how to analyze financial data programmatically, a valuable skill set for data-driven decision-making.

