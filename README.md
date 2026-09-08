# Can-Amazon-User-Ratings-Causally-Affect-Book-Prices
For my econometrics course, I investigated whether Amazon user ratings causally influence the price of bestselling books, using the "Amazon Top 50 Bestselling Books 2009–2019" dataset (Kaggle, 550 observations).

I built an OLS regression model controlling for genre, number of reviews (log-transformed), and repeat bestseller status (via a fixed effect for first year on the list and years-as-bestseller variable) to address omitted variable bias and reverse causality concerns. I also ran a log-price specification to check robustness.

User ratings showed no statistically significant effect on book price (p = 0.94)
Number of reviews also had no meaningful predictive power on pricing
Genre was the strongest driver of price & nonfiction books cost about $2.54 more than fiction on average
Results suggest bestseller pricing is shaped more by publisher conventions and Amazon's standardized pricing norms than by consumer ratings
