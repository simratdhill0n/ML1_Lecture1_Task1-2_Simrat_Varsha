# ML1 Lecture 1 - Task 1 & Task 2

**Students:** Simrat Pal Singh Dhillon, Varsha Jaikrishnan  
**Submission Name:** ML1_Lecture1_Task1&2_Simrat_Varsha

---

## Task 1 (Python Web Scraping)

For Task 1, we created a Python script that takes a Medium article URL as input and extracts the main text from the page.  
After running the script, it creates a folder called **scraped_articles** and saves the article content into a **.txt** file inside that folder.

### Input
- Medium article URL

### Output
- A text file (`.txt`) containing the scraped article content

### Libraries used
- `os` (for creating folders and saving files locally)
- `requests` (to fetch the webpage HTML)
- `BeautifulSoup (bs4)` (to parse the HTML and extract readable text)

### Submitted files
- Python script (`.py`)
- Scraped text file (`.txt`)

---

## Task 2 (GitHub + Notebook)

For Task 2, we converted the same web scraping solution into a Jupyter Notebook and then pushed all required files to our GitHub repository.  
We also followed the proper GitHub process by working in a separate branch, creating a pull request, and merging it into the main branch after review.

### Included files in GitHub
- Python script (`.py`)
- Scraped output file (`.txt`)
- Jupyter Notebook (`.ipynb`)

### GitHub workflow followed
- Created `task2.ipynb` and replicated Task 1 inside it
- Added a collaborator to the repository
- Created a branch named `github_task`
- Committed and pushed all three files to that branch
- Opened a Pull Request and requested review
- Merged the Pull Request into the `main` branch
