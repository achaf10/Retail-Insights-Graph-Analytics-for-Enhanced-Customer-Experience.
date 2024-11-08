# Retail Insights - Graph Analytics for Enhanced Customer Experiences

## 📊 Project Overview
This project applies graph analytics and machine learning to transaction data from a retail store, with the goal of enhancing customer satisfaction and optimizing worker interactions. By leveraging techniques such as PageRank, clustering, collaborative filtering, and frequent pattern mining, we uncovered insights that support strategic decision-making for improved customer experiences and increased sales.

---

## 🎯 Objectives
- **Identify Influential Transactions**: Discover key transactions that significantly impact customer satisfaction.
- **Segment Customer and Worker Data**: Classify customers and workers into clusters to reveal relationship patterns.
- **Predict Customer Preferences**: Use recommendation systems to suggest products customers are likely to buy.
- **Optimize Product Placement**: Identify frequently bought item pairs for strategic bundling and product positioning.

---

## 🔍 Key Insights

### 1. **Influential Transactions & Worker Impact**
   - **PageRank** analysis revealed workers with high influence on customer interactions. Worker ID 116, for instance, emerged as a key influencer, suggesting that using such workers for promoting high-value products (e.g., laptops) can enhance customer satisfaction.

### 2. **Customer Segmentation**
   - **K-means Clustering** segmented customers and workers into distinct clusters, helping identify common characteristics. This insight allows for targeted marketing and optimized worker performance based on the specific needs of each customer segment.

### 3. **Personalized Recommendations**
   - **Collaborative Filtering** predicted customer preferences for items they hadn’t yet purchased. High-prediction items (e.g., paperweights, pens) offer opportunities for targeted marketing that resonates with customer preferences.

### 4. **Product Bundling Opportunities**
   - **Frequent Pattern Mining** identified product combinations frequently bought together, such as paper clips and stickers, or mouse and mouse pads. Bundling these items can drive cross-selling and improve customer shopping experiences.

### 5. **Strategic Marketing Recommendations**
   - By setting confidence and lift thresholds, we identified optimal product groupings (e.g., headphones, mouse, mouse pad) that could be bundled in-store or promoted together in marketing campaigns for increased sales.

---

## 🛠️ Tools & Technologies
- **Data Processing**: PySpark, SQL GraphFrames
- **Machine Learning**: K-means Clustering, Collaborative Filtering
- **Pattern Mining**: Frequent Pattern Mining
- **Languages**: Python, SQL

---

## 📈 Methodology

- **Graph Analytics (PageRank)**: Used to rank influential transactions and workers, enabling a focus on impactful customer-worker interactions.
- **K-means Clustering**: Segmented data into customer and worker groups based on predictive values, uncovering natural groupings and behavioral patterns.
- **Collaborative Filtering**: Predicted items customers are likely to purchase based on transaction history, providing a basis for personalized recommendations.
- **Frequent Pattern Mining**: Analyzed co-purchasing behaviors to identify potential product bundles, aiding strategic inventory and product placement decisions.

---

## 📂 Project Structure
```plaintext
📦 retail-insights-graph-analytics
├── 📁 data                 # Contains raw and processed datasets
├── 📁 notebooks            # Jupyter notebooks with data analysis and model implementation
├── 📁 reports              # Project report and presentation files

