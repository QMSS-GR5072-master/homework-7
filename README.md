# homework 7 - webscraping

## Instructions

1. Your final document should be an `.md` file (GitHub-flavored markdown) knitted from an R Markdown file. Create a folder called `/homework` where you will add the `.md` file, and a folder called `/src` where you will  place the `.Rmd` file and any other scripts you used to create the reports.

  In answering each of the questions for the assignment please include
  - the question as a header in your R Markdown report,
  - the raw code that you used to generate any tables, and
  - the top ten rows of the resulting `tibble`. (Do not include more than ten rows for any table in your report).

2. when you are done with your final `push` to this repo, submit the link to this repo on Canvas. (Make sure to `commit` your progress throughout the day, and `push` your progress at the end of each day.)


### Assignment items `[100 pts]`

Use the the [`rvest`](https://rvest.tidyverse.org) package and the `Webscraping.R` script to scrape content from this [website](https://en.wikipedia.org/wiki/2019_NCAA_Division_I_Men%27s_Basketball_Tournament) and answer the following questions:

1. [`20 pts`] The text in the first header of the page

2. [`20 pts`] All links listed on the page.  Use `grep()` to return any links with "http" in the text of the link. How many links are there?

3. [`20 pts`] Scrape all tables listed on the page.  How many tables are there?  Extract and print the first ten rows of the first table.

4. [`20 pts`] Scrape all paragraphs on the page. How many paragraphs are there?  Extract the text of the paragraph nodes. Use `grep()` to search through all paragraph text and return all paragraphs with the word "championship" in the paragraph text.

5. [`20 pts`] The top right side of the webpage has a box had a title the reads "2019 NCAA Division I".  How would you use developer tools to determine the correct nodes to target to scrape this title?  Find the nodes or node names using developer tools and then scrape this text.  
