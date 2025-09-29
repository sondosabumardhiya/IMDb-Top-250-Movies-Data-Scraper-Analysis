# IMDb Top 250 Movies Data Scraper & Analysis

## Description
This project is for **educational purposes**.  
It is a Python-based **Data Engineering and Web Scraping pipeline** that extracts IMDb’s Top 250 Movies and their full cast & crew, cleans and transforms the data, merges it, and stores it into a MySQL database for structured analysis.

---

## Technologies Used
- **Python** – Programming language  
- **Requests & BeautifulSoup** – Web scraping  
- **Pandas** – Data cleaning and manipulation  
- **JSON** – Parsing structured data  
- **MySQL** – Data storage and structured access  
- **Scikit-learn** – Data transformation (encoding, normalization, standardization)  

---

## Notes
- Ensure MySQL server is running and credentials are updated in `load_to_mysql.py`.  
- The scraper uses polite delays (`time.sleep()`) to avoid overwhelming IMDb servers.  
- Data preprocessing handles missing values, removes duplicates, and standardizes columns for analysis.  

---

## Output Files
- `imdb_top_250_movies.csv` → Raw movie details  
- `full_cast_and_crew.csv` → Raw cast & crew details  
- `clean_imdb_top_250_movies.csv` → Cleaned and preprocessed movie dataset  
- `merged_imdb_cast_and_crew.csv` → Merged dataset ready for analysis  

---

## Install Dependencies
This step installs all required Python libraries for the project to run:  
```bash
pip install -r requirements.txt
