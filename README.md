```markdown
# Amazon Sales Dataset - Exploratory Data Analysis (EDA)

## Project Overview 📊

This project is part of a series titled "3 Days, 3 EDA Projects", where I conduct detailed Exploratory Data Analysis (EDA) on diverse datasets. For this project, I worked with the Amazon Sales Dataset, which contains ratings, reviews, and pricing data for over 1,000 Amazon products.

### Objective 🧠

The goal of this project is to explore and analyze the dataset to uncover meaningful insights into product performance, pricing strategies, customer sentiment, and more. This analysis will help businesses and decision-makers make data-driven decisions by understanding trends and patterns within the Amazon marketplace.

---

## Dataset Information 📑

- Source: The dataset consists of over 1,000 Amazon products.
- Features:
  - `product_id`: Product ID
  - `product_name`: Name of the Product
  - `category`: Category of the Product
  - `discounted_price`: Discounted Price of the Product
  - `actual_price`: Actual Price of the Product
  - `discount_percentage`: Percentage of Discount
  - `rating`: Rating of the Product
  - `rating_count`: Number of ratings
  - `about_product`: Product description
  - `user_id`: ID of the user who wrote the review
  - `user_name`: Name of the user who wrote the review
  - `review_id`: Review ID
  - `review_title`: Short review title
  - `review_content`: Detailed review content
  - `img_link`: Image link of the product
  - `product_link`: Official product page link

---

## Key Insights 🔍

### 1. Product Distribution and Categories
- Analysis of how products are distributed across categories.
- Identification of the most popular and frequently reviewed products.

### 2. Pricing and Discount Patterns
- Exploration of the relationship between actual price, discounted price, and discount percentages.
- Insights into pricing strategies and customer behavior.

### 3. Ratings and Reviews Analysis
- Examining product ratings and their correlation with the number of reviews.
- Analyzing the sentiment of customer reviews based on text analysis of review content.

### 4. Visualizations
- Multiple visualizations created to showcase patterns, trends, and anomalies in product ratings, pricing, and customer reviews.

---

## Tools & Libraries Used 🛠️

- Programming Language: Python
- Libraries:
  - `pandas`: For data manipulation and cleaning
  - `matplotlib` and `seaborn`: For data visualization
  - `numpy`: For numerical operations
  - `wordcloud`: For generating word clouds from review text
  - `nltk`: For natural language processing of review content
  - `scikit-learn`: For text analysis and possible sentiment analysis

---

## Installation and Setup 🖥️

To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-sales-eda.git
   ```
2. Navigate to the project directory:
   ```bash
   cd amazon-sales-eda
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```
4. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `Amazon_Sales_EDA.ipynb` to explore the analysis.

---

## Project Structure 📂

```
amazon-sales-eda/
│
├── data/
│   └── amazon_sales_dataset.csv          # Dataset file
│
├── images/
│   └── wordcloud.png                     # Visualization images (Optional)
│
├── notebooks/
│   └── Amazon_Sales_EDA.ipynb            # Jupyter notebook for EDA
│
├── README.md                             # Project documentation
├── requirements.txt                      # Python dependencies
└── LICENSE                               # License information
```

---

## How to Contribute 🤝

Contributions are welcome! If you have any improvements or additional insights that could enhance this project, feel free to open an issue or submit a pull request.

---

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments 🙏

- This dataset was sourced from the public domain and is not affiliated with or endorsed by Amazon.
- Thanks to the open-source community for the tools and libraries that made this project possible.

---

## Stay Connected 🌐

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/surabhi-jaiswal-97a539252/) or check out my other projects on [GitHub](https://github.com/Surabhi-Jaiswal).

---

### Enjoy the analysis! 🎉
```
