# Used Car Market Segmentation

Unsupervised ML project using K-Means on the CarDekho used-car dataset.

## Goal
Create useful inventory segments based on price, year, usage, efficiency, engine size, power, and seats.

## Techniques
Numeric extraction, median imputation, log transformation, standardization, K-Means, silhouette score, elbow method, cluster profiling and visualization.

## Model choice
`k=2` had the strongest silhouette score (~0.399), while **k=4** was selected for richer business interpretation and retained a reasonable score (~0.303).

## Segments
1. Premium / newer high-performance
2. Older budget
3. Newer mainstream efficient
4. Larger / utility-oriented

## Files
- `used_car_market_segmentation.ipynb` — complete executed notebook
- `Car_details_v3.csv` — dataset
- `requirements.txt`

## Portfolio skills
Python, pandas, feature transformation, scaling, unsupervised learning, clustering evaluation, visualization, business interpretation.
