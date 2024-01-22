# Web Scraping and Text Analysis

This Jupyter Notebook provides a solution for web scraping, text analysis, and sentiment analysis. The script extracts content from specified URLs, performs sentiment analysis, analyzes text complexity metrics, and provides additional insights.

## Installation

Make sure to install the required Python packages:

```bash
pip install requests beautifulsoup4 pandas nltk
```

## Usage

1. **Run the Web Scraping Script:** Execute the first part of the notebook to read URLs from 'Input.xlsx,' extract content, and save it to individual text files.

2. **Analyze Sentiment:** The notebook calculates sentiment scores (positive, negative, polarity, subjectivity) and saves the results.

3. **Text Complexity Metrics:** Measure text complexity metrics (average sentence length, percentage of complex words, Fog Index) for each file in 'TitleText.'

4. **Word Count and Pronoun Analysis:** Analyze word count, average word length, and count personal pronouns.

5. **DataFrame Creation:** Create a DataFrame from the calculated values and save it to 'Output_Data.csv.'

## Directory Structure

- Input.xlsx: Input file containing URLs and corresponding URL_IDs.
- TitleText: Directory to store extracted title and text files.
- StopWords: Directory containing stop words for sentiment analysis.
- MasterDictionary: Directory containing positive and negative words for sentiment analysis.
- Output Data Structure.xlsx: Excel file with predefined structure for output data.
- Output_Data.csv: CSV file containing calculated metrics.

## LinkedIn

Connect with me on LinkedIn: [![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin&colorB=2867B2)](https://www.linkedin.com/in/hardikjp/))

## Note

- Ensure proper directory paths in the code for file reading and writing.
- Some URLs might throw errors due to unavailability or structure changes.





