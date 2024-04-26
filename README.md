# MCAT Practice Questions Scraper

This Python script is a web scraper specifically designed for extracting MCAT (Medical College Admission Test) practice questions from [mcat-prep.com](https://www.mcat-prep.com/mcat-sample-questions/). The scraped data is organized into three lists: `questions`, `answers`, and `explanations`, making it easy to access and utilize for MCAT preparation. This script will serve a blueprint for future webscraping of NCMHCE Practice Exams as needed by the Social Well-being lab at the Georgia Institute of Technology. 

## Features

- **Web Scraping**: Utilizes web scraping techniques to extract MCAT practice questions from [mcat-prep.com](https://www.mcat-prep.com/mcat-sample-questions/).
- **Data Organization**: Organizes the scraped data into three lists: `questions`, `answers`, and `explanations`.
- **HTML Parsing**: Parses HTML structure to identify and extract relevant information such as questions, answer choices, and explanations.
- **Flexible Usage**: Can be easily integrated into other applications or scripts for further analysis or processing.

## Getting Started

To get started with using the MCAT Practice Questions Scraper, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/mcat-prep-scraper.git
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the scraper script, providing the URL of the [mcat-prep.com](https://www.mcat-prep.com/mcat-sample-questions/) website:
   ```bash
   python scraper.py https://www.mcat-prep.com/mcat-sample-questions/
   ```

4. Access the scraped data from the generated `questions.txt`, `answers.txt`, and `explanations.txt` files.

## Dependencies

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): A Python library for pulling data out of HTML and XML files.
- [Requests](https://docs.python-requests.org/en/latest/): A Python HTTP library for making HTTP requests.

## Contributing

Contributions to the MCAT Practice Questions Scraper are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or create a pull request.
