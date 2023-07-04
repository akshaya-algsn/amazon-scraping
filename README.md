# amazon-scraping


Amazon Product Scraping and Captcha Bypass
This repository contains Python scripts for scraping product details from Amazon using various web scraping techniques and bypassing the Amazon Captcha using Selenium. It is a submission for the coding round of Relu Consultancy's recruitment process.

Main Task
The main task involves scraping a minimum of hundred URLs in the format of "https://www.amazon.{country}/dp/{asin}" provided in a CSV file. The script utilizes libraries such as BeautifulSoup (bs4), Selenium, and requests to extract the following details from each page:

>Product Title
>Product Image URL
>Price of the Product
>Product Details

The script handles cases where a URL throws a 404 Error and skips those URLs. After each round of hundred URLs, the total time taken to complete the scraping process is displayed.

The output is in the form of a list of dictionaries and is represented in JSON format. Additionally, the script provides the option to connect to a database (e.g., MySQL or PostgreSQL) to dump the scraped data while still creating the output JSON file.

Bonus Task
The bonus task involves writing a script to bypass the Amazon Captcha. The script solves the captcha by finding the captcha input field and submitting the provided captcha solution. It uses Selenium and Chrome WebDriver in headless mode to interact with the captcha form.

Repository Structure
The repository is structured as follows:

main_task.ipynb: Jupyter Notebook containing the code for the main task.
bonus_task.ipynb: Jupyter Notebook containing the code for the bonus task.
urls.csv: CSV file containing the list of URLs to be scraped.
output.json: JSON file containing the scraped data in the desired format.
README.md: This file, providing an overview of the repository and instructions.
Usage
To run the main task, ensure you have Python (latest version), along with the required libraries (bs4, Selenium, requests). Modify the file path in the code to point to the urls.csv file. Execute the notebook to perform the scraping and generate the output JSON file.

For the bonus task, execute the bonus_task.ipynb notebook after installing the necessary dependencies.

Feedback and Contact
Your feedback is appreciated! If you have any questions or suggestions, feel free to reach out to me at akshayadevi63@gmail.com. Thank you for considering my submission.

You can customize this description by adding your email address, ensuring the contact information is accurate and professional. Additionally, you can modify the repository structure and usage section based on your specific implementation and preferences.

Make sure to update the repository's description on GitHub by following the steps mentioned earlier to include this comprehensive description.
