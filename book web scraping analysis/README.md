# Web Scraping and Data Analysis Project

This project is a **web scraping and data analysis task** designed to gather book-related data from the "Books to Scrape" website. The goal is to extract information like **book titles, star ratings, prices, availability, and URLs**, and analyze this data to gain insights into pricing trends, ratings distribution, and other metrics.

---

## Features

- **Scrapes** book titles, star ratings, prices, availability, and URLs.  
- **Dynamically extracts** book categories.  
- **Handles pagination** to scrape multiple pages.  
- **Filters** books with 4 and 5-star ratings priced below $20.  
- **Generates visualizations** for price distribution and star rating counts.  
- **Implements error handling** and timeouts to avoid server overload.

---

## Libraries Used

| Library        | Purpose                                                    |
| -------------- | ---------------------------------------------------------- |
| **requests**   | Fetches the HTML content from the website pages.            |
| **BeautifulSoup** | Parses and navigates the HTML structure to extract useful data. |
| **pandas**     | Organizes extracted data into structured format (DataFrame) and enables data analysis. |
| **time & random** | Adds randomized delays between requests to avoid overloading the server. |
| **matplotlib & seaborn** | Generates plots for visualizing the price and star rating distributions. |

---

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/username/web-scraping-books-analysis.git
    ```
2. Install the required libraries:
    ```bash
    pip install requests beautifulsoup4 pandas matplotlib seaborn
    ```
3. Run the script.

---

## Data Fields

The data extracted and saved includes:

- **Title**: The name of the book.
- **Star Rating**: A rating for the book (1 to 5 stars).
- **Price**: The price of the book in GBP.
- **Availability**: Stock status (e.g., In stock).
- **Book URL**: The direct link to the book's page.

---

## Output

- **CSV File**: The scraped data is saved to a file called `books2.csv`.  
- **Filtered Books**: Books with a star rating of 4 or 5 and priced below $20 are displayed.

---

## Visualizations

- **Price Distribution**: A histogram showing the price distribution of all books.
- **Star Rating Count**: A bar chart displaying the count of books by star rating.

---

## Error Handling

- Handles exceptions like **timeouts** and **invalid URLs**.
- Implements **delays** between requests to prevent overloading the server.

---

## Use Case

This project demonstrates how **web scraping** can be applied in real-world data analysis scenarios. The data extracted can be used for various analyses, such as:

- **Price trends** of books across different genres.
- **Correlation** between star ratings and book prices.
- **Availability analysis** of books.

---

## Contribution

Feel free to **fork** this project and contribute by adding additional features, such as:

- Extracting more data fields (e.g., book descriptions, number of reviews).
- Adding more advanced data visualizations.
- Optimizing the scraping process.

---

## License

This project is open-source and available under the **MIT License**.
