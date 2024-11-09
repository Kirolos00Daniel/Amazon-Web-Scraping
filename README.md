# Amazon Web Scraping Project

**Overview**  
This project involves web scraping Amazon's product listings for "PlayStation 4" to collect data on various listings, including product names, prices, ratings, and availability. The extracted data is stored in a CSV file for further analysis and research purposes.

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Extraction](#data-extraction)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Getting Started
These instructions will guide you on setting up the project and running the code on your local machine.

## Prerequisites
- **Python 3.7+**
- **Jupyter Notebook** or any compatible IDE to run `.ipynb` files
- **Libraries**: `requests`, `BeautifulSoup`, `pandas`
  - Install these libraries using:
    ```bash
    pip install requests beautifulsoup4 pandas
    ```

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/amazon-web-scraping.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd amazon-web-scraping
   ```
3. **Open the Jupyter Notebook**:
   - Use Jupyter Notebook to open `Amazon Web Scraping.ipynb` or `Amazon Web Scraping Sample.ipynb` files.

## Usage
1. **Run the Notebook**:
   - Execute the cells in the notebook to scrape the Amazon product page and extract data for "PlayStation 4" listings.
2. **Data Extraction**:
   - The scraped data will be saved in a CSV file named `amazon_data.csv`, which includes columns like product name, price, rating, and availability.

## Project Structure
- `Amazon Web Scraping.ipynb`: Main Jupyter Notebook for scraping data.
- `Amazon Web Scraping Sample.ipynb`: Sample notebook demonstrating the scraping process.
- `amazon_data.csv`: Output CSV file containing the scraped data.
- `image.png`: Screenshot of the Amazon search results page.
- ![Screenshot 2024-11-09 150014](https://github.com/user-attachments/assets/9a9030ea-edb6-44f2-9091-b329db8e93a1)


## Data Extraction
- **Data Fields**: The following fields are extracted for each product:
  - **Product Name**
  - **Price**
  - **Rating**
  - **Availability**

- **CSV Output**: The extracted data is stored in `amazon_data.csv`, making it easy to analyze and visualize the information.

## Visualizations
The following visualizations were created to provide insights into the data:

### Distribution of Product Ratings

![output](https://github.com/user-attachments/assets/a640d24c-4a74-4ec2-af28-1ed0f744e593)


### Distribution of Product Prices

![output](https://github.com/user-attachments/assets/429c3d6b-e254-4802-9928-c8934d1a2294)

### Scatter Plot of Price vs Rating

![output](https://github.com/user-attachments/assets/d9a1dd5b-2449-481f-97cf-e19d9f58c217)



## Contributing
1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/YourFeature`)
3. **Commit your changes** (`git commit -m 'Add feature'`)
4. **Push to the branch** (`git push origin feature/YourFeature`)
5. **Create a Pull Request**

## License
This project is licensed under the MIT License.

## Contact
For questions or support, please reach out to:
- **Your Name** Kirolos Daniel
- **Email**: kiroemad2389@gmail.com
