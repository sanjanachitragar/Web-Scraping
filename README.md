# 🛍️ Laptop Scraper 🖥️

This project is a web scraper built using Python, BeautifulSoup, and Pandas to extract information about laptops from the [LaptopsDirect](https://www.laptopsdirect.co.uk/ct/laptops-and-netbooks/laptops) website. It retrieves essential details such as the product name, price, link, and product details, and stores them in an Excel file.

## 🚀 Features

- 🔍 Scrapes product names, prices, and product details from the website.
- 🌐 Extracts the URL for each product and combines it with the root URL.
- 📝 Outputs the data into a neatly structured Excel file.
- 🧹 Handles missing data by setting default values like `n/a`.

## 🛠️ Technologies Used

- **Python** 🐍
- **BeautifulSoup** for web scraping 🌐
- **Pandas** for data manipulation 📊
- **Requests** for handling HTTP requests 🔗

## 📦 How to Use

1. **Clone the Repository** 📁
   ```bash
   git clone [https://github.com/your-username/laptop-scraper](https://github.com/sanjanachitragar/Web-Scraping).git
   ```

2. **Install Required Packages** 📦
   Install the required dependencies using `pip`:
   ```bash
   pip install requests beautifulsoup4 pandas openpyxl
   ```

3. **Run the Scraper** 🏃‍♂️
   Execute the Python script to scrape laptop data and export it to an Excel file:
   ```bash
   python scraper.py
   ```

4. **Check Output** 📊
   After running the script, the data will be saved in an Excel file named `results_single_page.xlsx` in the project directory.

## 🗂️ Project Structure

```bash
├── scraper.py               # Main scraping script
├── results_single_page.xlsx  # Output Excel file
├── README.md                # Project documentation
```
