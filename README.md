## WEB SCRAPING

This project is a Python-based web scraping script that extracts information about TV series from IMDb and stores it in a CSV file. It utilizes the requests library to make HTTP requests and BeautifulSoup for HTML parsing. The scraped data includes series names, release years, ratings, and genres.

## Prerequisites
  Before running the script, ensure you have the following prerequisites installed: - Python 3
  Required Python libraries (requests, BeautifulSoup, pandas), which can be installed using pip: (pip install, sudo apt-get install python3) - beautifulsoup4, pandas

## Usage
  Clone the repository or download the script (web_scraping_imdb.py) to your local machine.
  Open the script in a Python IDE or text editor.
  Run the script to initiate the web scraping process. The script will fetch data from IMDb and save it as a CSV file named 18it106-web-scraping.csv in the same directory.
  python web_scraping_imdb.py

## Output
  The CSV file generated (18it106-web-scraping.csv) will contain the following columns:

  Series Name
  Release Years
  Ratings
  Genre

## Example
Here's a snippet of what the CSV file might look like:

| Series Name                    | Release Years  | Ratings | Genre                               |
|--------------------------------|----------------|---------|-------------------------------------|
| Star Trek: The Next Generation | (1987–1994)    | 8.6     | Action, Adventure, Mystery          |
| Seinfeld                       | (1989–1998)    | 8.8     | Comedy                              |
| Twin Peaks                     | (1990–1991)    | 8.8     | Crime, Drama, Mystery               |
| The Simpsons                   | (1989– )       | 8.6     | Animation, Comedy                   |
| Mr. Bean                       | (1990–1995)    | 8.5     | Comedy, Family                      |
...

**Author** devanshu3