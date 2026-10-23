# Gaurav's Amazon Product Analytics

## Project overview
This IBM Data Analytics project explores an Amazon India product-listing dataset using Python. It studies category mix, discounted and actual prices, listed discounts, ratings, and review counts.

## Dataset
- File: `data/amazon.csv`
- Rows: 1465
- Columns: 16
- Source: user-provided CSV file. Keep the dataset with the notebook when running the project.
- The dataset contains product identifiers, names, category hierarchy, prices, discount percentages, ratings, rating counts, product descriptions, review fields, and product/image links.

## Tools
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## How to run
1. Install Python 3.10+.
2. Download/clone this repository.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open `Gaurav_Amazon_Product_Analytics.ipynb` and run the cells from top to bottom.

The notebook expects the CSV at `data/amazon.csv` (or `amazon.csv` beside the notebook).

## Project workflow
1. Data loading and inspection
2. Missing-value and duplicate checks
3. Cleaning numeric fields containing currency symbols, commas, and percent signs
4. Category-level summaries
5. Price and discount analysis
6. Rating and review-count analysis
7. Correlation analysis
8. Evidence-based recommendations and limitations

## Responsible interpretation
The analysis is descriptive and applies only to the supplied dataset snapshot. Listed discounts and review counts are not proof of sales, profit, or customer satisfaction. The data does not contain transaction-level sales or profit.

## Repository layout
```text
Gaurav_Amazon_Product_Analytics/
├── Gaurav_Amazon_Product_Analytics.ipynb
├── requirements.txt
├── README.md
├── Project_Report.docx
└── data/
    └── amazon.csv
```

## Author
Gaurav
