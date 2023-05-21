# WorkJam Schedule Scraper

This project is a WorkJam schedule scraper that automates the process of retrieving your work schedule from the WorkJam platform. It simplifies the task of managing and tracking your work-life schedule by providing a convenient way to extract and store schedule information.

## Blog Post

For a detailed step-by-step guide on how to build this WorkJam schedule scraper and automate your work-life, refer to the [blog post](https://medium.com/@ahmad38sal/from-hassle-to-ease-building-a-workjam-schedule-scraper-to-automate-your-work-life-a3dcc5c93c92).

## Features

- Automated retrieval of your work schedule from WorkJam.
- Extracts schedule information, such as shift timings, dates, and locations.
- Stores the extracted schedule data for easy access and tracking.

## Prerequisites

To use this WorkJam schedule scraper, you need to have the following:

- Python 3 installed on your system.
- Beautiful Soup and Selenium libraries installed. You can install them using the following command:

pip install beautifulsoup4 selenium


- Access to a WorkJam account with your work schedule.

## Getting Started

1. Clone the repository:

git clone https://github.com/ahmad38sal/ScheduleScraper.git


2. Navigate to the project directory:

cd workjam-schedule-scraper


3. Configure the scraper:

- Open the `config.py` file and provide your WorkJam login credentials.
- Adjust any other settings or preferences as needed.

4. Run the scraper:

python scraper.py


The scraper will automatically retrieve and store your work schedule data.

## Data Storage

The extracted schedule data will be stored in a structured format, such as a CSV file or a database, for easy access and further analysis. Refer to the blog post for more details on data storage options.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the scraper, feel free to submit a pull request.


Make sure to install the Beautiful Soup and Selenium libraries by running pip install beautifulsoup4 selenium before using the scraper.



