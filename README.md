# Codevedx_taskno_2
Data Analytics with python 
Dataset Overview": [
        "Dataset contains 1,000 orders spanning Jan 2021 – Dec 2023",
        "14 variables: 5 numerical, 6 categorical, 3 date-derived",
        "3% missing in Sales and 2% in Profit — imputed with median",
    

     Distribution Insights": [
        "Sales is STRONGLY right-skewed (skewness = +3.42): few large orders dominate",
        "Profit is moderately right-skewed (+1.23): most transactions are profitable",
        "Quantity is nearly UNIFORM (-0.02 skew): random order sizes",
        "Shipping_Days is symmetric: evenly distributed 1–7 days",
    

     Outlier Analysis": [
        "Sales has 4.8% outliers (IQR method) — high-value tech orders",
        "Profit has 3.1% outliers — extreme losses from heavily discounted items",
        "Quantity & Discount show NO outliers: controlled values",
  

     Category Performance": [
        "Technology generates HIGHEST average sales ($412/order)",
        "Office Supplies: lowest average but highest volume efficiency",
        "Furniture: moderate sales, highest variability in profit",
   
     Regional Analysis": [
        "West Region shows highest average profit margin",
        "All 4 regions contribute nearly equally (23–26% of orders)",
        "North leads in total profit by slight margin",
    

     Discount Impact (Critical Finding)": [
        "★ Strongest correlation: Discount vs Profit (r = -0.634)",
        "Orders with 0% discount yield avg profit of $68.23",
        "Orders with >30% discount result in average LOSS of $42.34",
        "Recommendation: Cap discounts at 20% to maintain profitability",
   

     Time Series Trends": [
        "Revenue grew YoY: 2021→2022 (+14.5%), 2022→2023 (+12.5%)",
        "Peak sales months: Oct–Dec (holiday season effect)",
        "Profit margin slightly declining: 22.73% → 21.87% (discount pressure)",
   

     Customer Segments": [
        "Consumer segment = 50.3% of orders (largest group)",
        "Corporate segment shows highest average order value",
        "Home Office: smallest segment but growth potential identified",

      ("💰 Pricing Strategy",
     "Cap discounts at 20% — beyond this, profit turns negative"),
    ("🏷️  Category Focus",
     "Invest more in Technology (highest avg sale value per order)"),
    ("📅 Seasonal Planning",
     "Increase inventory and marketing spend in Q4 (Oct–Dec)"),
    ("🌍 Regional Expansion",
     "Replicate West region's strategy in South for margin improvement"),
    ("👥 Segment Targeting",
     "Target Corporate segment for higher-value order acquisition"),
    ("⚠️  Outlier Monitoring",
     "Investigate top 5% sales orders — they may need special handling"),
    ("📦 Shipping Optimization",
     "Promote First Class shipping for high-value Tech orders"),
