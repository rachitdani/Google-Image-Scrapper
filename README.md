# Google-Image-Scrapper
This website scrapes top 20 google images and also stores it in my mongodb in bin format

## About the Project

The Image Web Scraper is a web application that allows users to enter a name and scrape the top 20 images obtained from google images. This project is built using web scraping techniques and technologies such as Python, Flask, and BeautifulSoup.

Key features of this application include:

- Basic interface: A simple interface that allows users to enter the product name and initiate the scraping process.
- Real-time scraping: The application performs real-time web scraping on Google Images to retrieve the latest images.

## Getting Started

To run this project locally or contribute to its development, follow the steps below:

### Prerequisites

Before you begin, ensure you have the following prerequisites installed on your system:

- flask
- flask_cors
- requests
- bs4
- pymongo
- gunicorn==20.1.0

You can install the required Python packages using `pip`. For example:

```
pip install -r requirements.txt
```

### Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/rachitdani/Google-Image-Scrapper.git
```

2. Change the directory to the project folder:

```
cd Google-Image-Scrapper
```

3. Run the application locally:

```
python app.py
```

4. Open your web browser and access the application at `http://localhost:8000/review`.

## Usage

1. Open the web application in your web browser.

2. Enter the name for which you want to scrape the images .

3. Click the "Search" or "Scrape Reviews" button.

4. The application will scrape images and store in the images folder along with the images bin file updated in mongodbdatabase.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.

2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name` or `git checkout -b bugfix/your-bug-fix`.

3. Make your changes and commit them with meaningful commit messages.

4. Push your changes to your forked repository.

5. Create a pull request to merge your changes into the main repository.
