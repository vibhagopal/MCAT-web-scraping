# MCAT Practice Questions Scraper

This Python script serves as a web scraper tailored to extract MCAT (Medical College Admission Test) practice questions from [mcat-prep.com](https://www.mcat-prep.com/mcat-sample-questions/). The scraper is capable of retrieving questions, answer choices, correct answers, and explanations from the specified webpage. This script serves as a blueprint for future webscrabing of NCHMCE Practice Exams as needed by the Social Well-being Lab at the Georgia Institute of Technology. 

## Features

- **Web Scraping**: Utilizes requests and Beautiful Soup to scrape practice questions from the target website.
- **Data Extraction**: Extracts questions, answer choices, correct answers, and explanations from the HTML structure of the webpage.
- **Robust Parsing**: Utilizes HTML parsing techniques to locate and extract relevant content, ensuring accurate retrieval of MCAT practice materials.
- **Customizable**: Easily adaptable to accommodate changes in the website's HTML structure or to scrape practice questions from similar webpages.

## Usage

To utilize the MCAT Practice Questions Scraper:

1. Clone or download the repository to your local machine.
2. Ensure you have Python installed along with the required dependencies (`requests`, `Beautiful Soup`).
3. Open the script and specify the URL of the [mcat-prep.com](https://www.mcat-prep.com/mcat-sample-questions/) webpage containing the practice questions.
4. Run the script to scrape the practice questions along with their associated data.
5. Access the extracted questions, answer choices, correct answers, and explanations for MCAT preparation.

## Important Notes

The following is the HTML code provided by [mcat-prep.com](https://www.mcat-prep.com/mcat-sample-questions/). This script utilizes the DOM to scrape relevant information.

<div align="center">
  <img src="https://private-user-images.githubusercontent.com/105722844/326023799-52fe0ca5-27a3-4922-9d1f-3459bff82b0b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQxNDQzMTQsIm5iZiI6MTcxNDE0NDAxNCwicGF0aCI6Ii8xMDU3MjI4NDQvMzI2MDIzNzk5LTUyZmUwY2E1LTI3YTMtNDkyMi05ZDFmLTM0NTliZmY4MmIwYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNDI2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDQyNlQxNTA2NTRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NDQ1Nzc5N2M3MWE4MDViZWZiY2I0NTg0ZjVhZmIwNmQ1ZGIzNTMxYjdiYjJlNjNiZDMwMWFlMmIwMzBkYTU4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ZM9peWn7F_Mq9yZQiy80ugDAifbbNi-Mj" alt="Image Description">
</div>



## Contributing

Contributions to the MCAT Practice Questions Scraper are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or create a pull request.
