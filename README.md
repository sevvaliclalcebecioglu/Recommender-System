# Medical Product Recommendation System

This project focuses on developing a **recommendation system** for a medical supplies company to boost sales. By analyzing past sales data, the system provides personalized recommendations for customers and products.

---

## Project Approaches

1. **Popularity-Based Recommendation**
   - Identifies the best-selling products and recommends them to all customers.

2. **User-Based Recommendation (Matrix Factorization / SVD)**
   - Generates personalized product recommendations using customer and product interaction data.

3. **Product Similarity-Based Recommendation (Content-Based / Cosine Similarity)**
   - Recommends products similar to a given product based on descriptions or attributes.

**Outcome:** The system can increase sales, improve customer satisfaction, and optimize inventory management.

---

## Project Report

### Objective
Enhance company sales and develop recommendation systems by analyzing customer behavior and product data.

### Steps Taken

1. **Data Preparation**
   - Checked for missing values; all relevant columns were utilized.
   - Prepared customer, order, and product data for analysis.

2. **Popular Product Analysis**
   - Ranked products by quantity sold and total revenue.
   - Identified top-selling and revenue-generating products.

3. **Top Purchasing Companies**
   - Ranked companies by purchase quantity and total value.
   - Determined customers with the highest sales volume.

4. **Popularity-Based Recommendation**
   - Generated product recommendations based on sales volume and revenue.

5. **Matrix Factorization-Based Recommendation**
   - Created a customer-product pivot table.
   - Applied matrix factorization and correlation analysis to generate personalized recommendations.

6. **Cosine Similarity Based on Product Descriptions**
   - Converted product descriptions into numerical vectors.
   - Calculated similarities between products using cosine similarity to provide content-based recommendations.

---

## Results

- No missing data; data preparation completed successfully.
- Product and customer analyses enabled a working popularity-based recommendation system.
- Matrix factorization and content similarity-based systems provided alternative recommendation models.
- These approaches can help optimize sales strategies and decision-making for the company.
