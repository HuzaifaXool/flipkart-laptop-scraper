# flipkart-laptop-scraper
This repository contains a web scraper for extracting laptop information from Flipkart, including laptop name, price, and ratings. The data is stored in a CSV file for easy access and analysis.

## Description

This project scrapes laptop information from Flipkart, including the laptop name, price, and ratings. The scraped data is saved into a CSV file.

## Data Fields

The following fields are extracted:

- **Laptop Name**: The name and model of the laptop.
- **Price**: The price of the laptop in Indian Rupees (₹).
- **Rating**: The average user rating of the laptop.
- **Ratings & Reviews**: The total number of ratings and reviews.

  ## Dependencies

- Python 3.x
- BeautifulSoup
- Requests
- Pandas
- selenium

## Example Data

Here's an example of the data structure stored in the CSV file:

|  Laptop Name                                      | Price   | Rating |  Ratings & Reviews           |
|---------------------------------------------------|---------|---------------------------------------|
| Lenovo IdeaPad Slim 3 Intel Core i3 12th Gen 1... | ₹35,990 | 4.2    | 1,011 Ratings & 60 Reviews   |
| DELL Inspiron 3520 Intel Core i3 12th Gen 1215... | ₹37,550 | 4.2    | 1,453 Ratings & 131 Reviews  |
| Lenovo IdeaPad Slim1 (2024) AMD Ryzen 5 Hexa C... | ₹35,990 | 4.2    | 4,006 Ratings & 393 Reviews  |
| Lenovo IdeaPad Slim 1 AMD Ryzen 5 Hexa Core 55... | ₹38,990 | 4.2    | 4,006 Ratings & 393 Reviews  |
