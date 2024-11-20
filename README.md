# **Business Performance Insights: Revenue, Customers, and Global Demand**

## **Overview**
This Power BI project analyzes business performance metrics, providing actionable insights for the CEO and CMO of an online retail store. The dashboard focuses on revenue trends, customer behavior, and market demand to support strategic decision-making.

---

## **Key Insights**

### **1. Seasonal Revenue Trends for 2011**
- **Visual**: Line Chart - *2011 Monthly Revenue Trends*
- Revenue remained steady (~$685,000/month) during the first 8 months.
- Significant growth observed from September to November, peaking at $1.5 million.
- Insightful for forecasting and planning marketing campaigns.

### **2. Sales Distribution by Day of the Week**
- **Visual**: Clustered Column Chart - *Sales Distribution by Day of the Week*
- **Key Observations**:
  - Thursday has the highest sales at $2.04M, followed closely by Tuesday at $1.99M.
  - Weekdays (Thu-Mon) show significantly higher sales compared to Sunday.
  - Sunday has the lowest performance at $0.76M, less than half of any weekday.
- **Business Insights**:
  - Customer activity favors weekdays, suggesting a B2B focus or work-hour-dependent service.
  - The significant Sunday drop suggests the business is not retail/consumer-focused.
  - Peak sales on Thursday and Tuesday could indicate work-related planning or purchasing patterns.
- **Recommendations**:
  - Focus resources and staffing on peak days (Thu-Tue).
  - Investigate factors driving Thursday and Tuesday performance.
  - Evaluate Sunday operations for cost-effectiveness or consider promotions for slow days.

### **3. Top 10 Countries by Revenue (Excluding UK)**
- **Visual**: Stacked Bar Chart - *Top 10 Countries by Revenue and Quantity Sold*
- Netherlands, Germany, Ireland, and France are high-performing regions.
- Suggested focus areas for growth and marketing strategies.

### **4. Top 10 Customers by Revenue**
- **Visual**: Donut Chart - *Top 10 Customers by Revenue*
- Balanced revenue dependency, with top customers contributing marginally more.
- Indicates low bargaining power of customers, providing stability.

### **5. Total Revenue by Item Description**
- **Visual**: Pie Chart - *Top 5 Items by Revenue*
- **Key Revenue Breakdown**:
  1. POSTAGE: $69.19K (36.11%) - Highest revenue generator.
  2. Manual: $42.82K (22.35%).
  3. Regency Cakes: $32.21K (16.81%).
  4. Rabbit Night Light: $28.88K (15.07%).
  5. Round Snack Box: $18.5K (9.66%) - Lowest contributor.
- **Key Insights**:
  - Heavy revenue concentration in top 2 items (POSTAGE and Manual, ~60%).
  - A mix of functional (POSTAGE, manuals) and decorative items (Rabbit Night Light).
  - High shipping activity suggests a mail-order or e-commerce business model.
- **Recommendations**:
  - Expand successful POSTAGE and Manual segments.
  - Investigate underperformance of Round Snack Box.
  - Explore bundling high and low-performing items.

### **6. Global Product Demand by Region**
- **Visuals**: Clustered Column Chart & Map - *Global Demand Distribution*
- Europe and Australia lead in demand, while Africa, Asia, and Russia show untapped potential.
- Recommendations for expansion strategies targeting untapped regions.

---

## **Features**
- **Interactive Dashboard**: Users can filter data by time (year/month).
- **Granular Insights**: Focused visuals for revenue trends, customer performance, and product demand.
- **Exclusions**: Data excludes the UK to emphasize growth opportunities.

---

## **Challenges**
- Handling inconsistent data with negative values for unit prices and quantities.
- Excluding the UK data for a more focused analysis.
- Designing a dashboard layout to ensure insights are accessible without scrolling or excessive interaction.

---

## **Technology Stack**
- **Power BI**: Data visualization and dashboard design.
- **Data Cleaning**: Removal of invalid entries (negative values).
- **Data Source**: Online Retail dataset for 2011.

---

## **How to Use**
1. Clone this repository:  
   ```bash
   git clone [repository_url]




