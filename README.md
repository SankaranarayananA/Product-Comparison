
# Product Comparison

This Python program allows users to compare products from different ecommerce websites by scraping product information from the websites.



## Requirements
Before running the program, make sure you have the following dependencies installed:

- Python (version 3.6 or above)
- Beautiful Soup 4 (beautifulsoup4)
- Requests (requests)
You can install the required packages using pip.
## Installation

- Clone this repository to your local machine or download the product_comparison.py file.
- Navigate to the directory where thefile is located.Run the program using the following command:

```bash
  py -m venv env 
  .\env\Scripts\activate
```
```bash
py -m pip install -r requirements.txt
py main.py
```
- The program will prompt you to enter the product name you want to compare.After entering the product name, the program will start scraping the product information from multiple ecommerce websites.
- The scraped information will be displayed in the console, including product name, price, and other relevant details from each website.The program will automatically generate a comparison report and save it to a file named product_comparison_report.txt in the same directory.
    
## Supported Ecommerce Websites
Currently, the program supports scraping product information from the following ecommerce websites:

- Amazon
- eBay
- Walmart
- Best Buy

Please note that due to website layout changes or other factors, the program may encounter issues with scraping from these websites. The program will be updated regularly to ensure compatibility with the latest website changes.


## Disclaimer

This program is intended for educational and personal use only. Scraping data from websites without permission may violate the website's terms of service. Use this program responsibly and only on websites that allow web scraping. The developers are not responsible for any misuse of this program.
## Contributing

Contributions are always welcome!

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the GitHub repository.

Please adhere to this project's `code of conduct`.


## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/SankaranarayananA/Product-Comparison/blob/da0af29cbd80b15ee7057181d58d1cc4e76a46af/LICENSE) file for details.
[MIT](https://choosealicense.com/licenses/mit/)

