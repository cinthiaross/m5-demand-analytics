📊 Sales Demand Exploration & Analytics Engineering Case

M5 Retail Dataset

1. Business Context

Retail organizations operate with thousands of SKUs across multiple locations and time periods.
In this context, understanding demand concentration, volatility, and calendar-driven behavior is critical for:

Inventory planning

Promotion strategy

Operational prioritization

Data-driven decision making at scale

This project focuses on exploring large-scale transactional sales data to uncover structural demand patterns that can guide commercial and operational decisions.

2. Objective

The objective of this project is to analyze historical retail sales data in order to:

- Identify demand concentration and long-tail behavior

- Understand volatility and stability across product categories

- Evaluate event-driven vs. regular demand patterns

- Generate insights that could inform inventory, pricing, and operational strategies

⚠️ This project intentionally does not include forecasting.
The focus is on exploratory analytics and decision support, not prediction.

3. Dataset

Source: M5 Forecasting – Accuracy (Kaggle:https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)

Granularity: Daily sales by item, category, store, and state

Time Horizon: Multiple years of historical data

Scale: Tens of thousands of time series

The dataset structure allows analysis at multiple aggregation levels, enabling hierarchical and comparative insights.

4. Analytical Approach

The analysis follows a structured analytics engineering mindset:

Data Understanding

Schema exploration

Identification of relevant dimensions and measures

Multi-Level Aggregation

Item-level

Category-level

Store and state-level

Demand Concentration Analysis

Identification of Pareto / long-tail behavior

Contribution of top products to total volume

Volatility & Stability Analysis

Comparison across categories

Identification of stable vs. elastic demand segments

Calendar & Event Impact

Sales behavior on event vs. non-event days

Category-specific sensitivity to calendar effects

This approach emphasizes interpretability and business relevance over model complexity.

5. Key Insights

Some of the main findings include:

A small percentage of products account for a disproportionate share of total sales, exhibiting strong Pareto behavior.

Non-discretionary categories tend to show lower volatility and more predictable demand patterns.

Event-driven sales increases are heterogeneous: not all categories benefit equally from calendar effects.

High-volume items are not necessarily the most volatile, highlighting the importance of separating volume from instability.

Aggregation level matters: insights differ significantly between item-level and category-level views.

6. Technology Stack

Python: pandas, numpy, matplotlib

Jupyter Notebooks: exploratory and analytical workflows

Visualization: static plots focused on interpretability

The project is designed to be tool-agnostic, prioritizing analytical logic over platform dependency.
