# Revenue Concentration & Customer Retention Analysis (SQL Project)

An end-to-end PostgreSQL analysis evaluating revenue distribution, customer retention dynamics, and structural business risk in an e-commerce marketplace.

---

## Business Context

Sustainable growth in e-commerce depends on understanding where revenue truly comes from.

Many businesses scale revenue without identifying:

- Revenue concentration risk  
- Dependency on repeat customers  
- Exposure to customer churn  
- Category-level structural risk  

This project analyzes these factors using PostgreSQL.

---

## Dataset

Public Olist Brazilian E-commerce Dataset.

Tables used:

- orders  
- order_items  
- customers  
- products  

Data was modeled and joined using relational database principles.

---

## Analytical Approach

The analysis was structured around business-driven questions.

---

### 1. Total Revenue

Aggregated order item price and freight value to determine overall business scale.

**Purpose:**  
Establish financial baseline.

---

### 2. Revenue per Customer

Calculated customer-level revenue using multi-table JOIN operations.

**Purpose:**  
Understand revenue distribution and customer value variability.

---

### 3. Top Revenue-Generating Customers

Ranked customers by revenue contribution.

**Purpose:**  
Identify high-value customer segments.

---

### 4. Repeat vs One-Time Customers

Segmented customers based on purchase frequency.

**Purpose:**  
Evaluate retention dynamics and customer behavior patterns.

**Business Insight:**  
Repeat customers play a critical role in revenue stability.

---

### 5. Pareto Analysis (80/20 Rule)

Used window functions and cumulative revenue calculations to measure revenue concentration.

**Business Insight:**  
A relatively small percentage of customers generates a disproportionate share of total revenue, indicating structural dependency risk.

---

### 6. Revenue by Product Category

Aggregated revenue at category level.

**Business Insight:**  
Revenue concentration within limited categories increases vulnerability to market or supply-side shocks.

---

## Key Findings

- Revenue is concentrated among a limited segment of customers.
- Repeat customers disproportionately contribute to financial performance.
- Both customer-level and category-level concentration expose the business to structural risk.
- Retention strategy is essential for long-term sustainability.

---

## Strategic Recommendations

- Strengthen customer loyalty and retention programs.
- Monitor revenue concentration metrics regularly.
- Diversify product category exposure.
- Invest in customer lifetime value optimization.

---

## Technical Skills Demonstrated

- PostgreSQL
- Complex JOIN operations
- Aggregations (SUM, COUNT, GROUP BY)
- Window Functions
- CTEs (Common Table Expressions)
- Business-oriented analytical thinking

---

## Repository Structure

- retention_analysis.sql → Complete SQL analysis
- README.md → Project documentation

---

## Author
Estevez Enzo
Data Analyst focused on data-driven decision making, business strategy, and customer behavior analytics.
