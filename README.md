# Wikipedia Data Extraction Automation

## What You're Aiming For

The objective is to automate the extraction of HTML content, article titles, text, and internal links from Wikipedia pages into a consolidated function that accepts any Wikipedia URL for efficient data retrieval and processing.

---

## Instructions

Create a Python script to automate data extraction from Wikipedia pages. The script will:

* Retrieve HTML content
* Extract article titles and text
* Collect internal links
* Consolidate all tasks into a single function that accepts a Wikipedia URL

This script will be tested on a specific Wikipedia page to validate its functionality.

---

### Tasks

1. Write a function to **get and parse HTML content** from a Wikipedia page.

2. Write a function to **extract the article title**.

3. Write a function to **extract the article text**, grouping each paragraph with its respective heading.

   * Map headings to their corresponding paragraphs using a dictionary.

4. Write a function to **collect every link** that redirects to another Wikipedia page.

5. Wrap all the previous functions into **one single function** that takes a Wikipedia link as a parameter.

6. Test the final function on a **Wikipedia page of your choice**.

---

## Notes

* The script should be modular and reusable.
* Ensure clean and readable data structures.
* Focus on automation and scalability.
