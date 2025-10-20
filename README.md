# Customer Segmentation Analysis - Logistics Insurance

## 🎯 **Project Overview**

This repository contains a comprehensive customer segmentation analysis for a logistics insurance company specializing in cargo and container coverage. The project uses machine learning clustering techniques to identify distinct customer groups and develop targeted commercial strategies.

### **Business Objective**
Analyze customer behavior patterns to identify distinct segments that require different commercial approaches, enabling data-driven decision making for pricing, retention, and service delivery strategies.

### **Key Results**
- **4 distinct customer segments** identified using K-means clustering
- **Clear differentiation** in revenue potential, risk profiles, and loyalty patterns
- **Actionable insights** for targeted commercial strategies
- **Interactive dashboard** for ongoing portfolio monitoring

---

## 📊 **Project Results Summary**

### **Customer Segments Identified**

| Segment | Size | Avg Revenue | Loss Ratio | Renewal Rate | NPS Score | Key Characteristics |
|---------|------|-------------|------------|--------------|-----------|-------------------|
| **Premium Partners** | 279 (27.9%) | $48,139 | 21% | 94% | 7.7 | Large fleets, international routes |
| **Efficient Operators** | 419 (41.9%) | $18,603 | 52% | 82% | 3.5 | General cargo, urban routes |
| **Growth Potential** | 166 (16.6%) | $17,376 | 54% | 79% | 2.6 | Perishable cargo, specialized ops |
| **High Risk** | 136 (13.6%) | $14,838 | 56% | 28% | 1.7 | Critical retention issues |

### **Business Impact**
- **Premium Partners** generate 3x higher revenue with exceptional loyalty
- **High Risk** segment shows critical retention problem requiring immediate intervention
- **Growth Potential** segment offers opportunities for specialized service expansion
- **Efficient Operators** represent stable, high-volume business foundation

---

## 🛠 **Technical Implementation**

### **Technologies Used**
- **Python:** pandas, scikit-learn, numpy, matplotlib, seaborn
- **Machine Learning:** K-means clustering with optimal K selection
- **Data Analysis:** Statistical validation and business interpretation
- **Visualization:** Interactive dashboards and executive reporting

### **Project Structure**
```
├── data/
│   └── customers_data.csv                    # Customer dataset (anonymized)
├── customer_segmentation_analysis.ipynb     # Complete analysis workflow
├── dashboards/
│   ├── customer_dashboard.png               # Executive dashboard visualization
│   └── skholl_dashboard.png                 # Interactive dashboard export
└── README.md
```

## 📊 **Complete Analysis Workflow**

The entire analysis is contained in a single comprehensive Jupyter notebook that covers:

### **Section 1: Data Loading & Quality Assessment**
- Dataset import and initial validation
- Data quality checks and basic statistics
- Missing value and duplicate analysis

### **Section 2: Exploratory Data Analysis**
- Distribution analysis of key variables
- Customer behavior pattern identification
- Business insights from data exploration

### **Section 3: Feature Engineering**
- Business metric calculations (RFM analysis)
- Risk scoring and operational complexity metrics
- Customer value and loyalty indicators

### **Section 4: Customer Segmentation**
- Feature selection and correlation analysis
- K-means clustering with optimal K determination
- Statistical validation using silhouette analysis

### **Section 5: Business Interpretation**
- Segment characterization and naming
- Strategic recommendations by customer group
- Dashboard visualization and reporting

### **Section 6: Implementation Framework**
- Business impact projections
- Implementation roadmap
- Next steps and ongoing development

---

## 📈 **Key Findings**

### **Statistical Validation**
- **Silhouette Score:** 0.361 (acceptable cluster separation)
- **Business Validation:** 94% alignment with expert assessment
- **Segment Stability:** Consistent patterns across time periods

### **Commercial Insights**

#### **🏆 Premium Partners (High Value)**
- **Strategy:** Retain at all costs with premium service
- **Characteristics:** Large fleet operations, international scope, high digital adoption
- **Revenue Impact:** Highest LTV potential, justify premium pricing

#### **⚖️ Efficient Operators (Volume Base)**
- **Strategy:** Optimize efficiency and scale operations
- **Characteristics:** Standard logistics, urban routes, price-conscious
- **Revenue Impact:** Largest segment, focus on operational efficiency

#### **💎 Growth Potential (Expansion Opportunity)**
- **Strategy:** Develop specialized products and services
- **Characteristics:** Perishable cargo, niche operations, good loyalty foundation
- **Revenue Impact:** Premium pricing opportunities through specialization

#### **⚠️ High Risk (Intervention Required)**
- **Strategy:** Immediate retention programs or managed exit
- **Characteristics:** Poor satisfaction, payment issues, high churn
- **Revenue Impact:** Potential negative LTV, requires urgent attention

---

## 🚀 **Implementation Recommendations**

### **Phase 1: Foundation (Completed)**
✅ Customer segmentation model deployed  
✅ Business segment characterization  
✅ Executive dashboard developed  
✅ Strategic framework established  

### **Phase 2: Optimization (In Progress)**
🔄 Customer Acquisition Cost (CAC) analysis by segment  
🔄 Lifetime Value (LTV) modeling and validation  
🔄 Pilot testing of differentiated strategies  

### **Phase 3: Advanced Analytics (Future)**
🎯 Predictive churn modeling  
🎯 Dynamic pricing optimization  
🎯 Automated prospect scoring  

---

## 💻 **How to Run**

### **Prerequisites**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly
```

### **Execution Steps**
1. Clone the repository
2. Install required dependencies
3. Open `customer_segmentation_analysis.ipynb`
4. Run all cells in sequence:
   - Data loading and quality assessment
   - Exploratory data analysis
   - Feature engineering and selection
   - K-means clustering analysis
   - Business segment interpretation
   - Dashboard visualization
5. Review outputs and generated visualizations

### **Data Requirements**
- Historical customer data (minimum 2 years recommended)
- Policy information (premiums, renewals, coverage)
- Claims data (amounts, frequency, types)
- Operational metrics (fleet sizes, routes, cargo types)

---

## 📊 **Visualizations**

### **Executive Dashboard**
![Customer Segmentation Dashboard](dashboards/customer_dashboard.png)

The dashboard provides:
- **Portfolio Overview:** Distribution and key metrics by segment
- **Performance Analysis:** Revenue, risk, and loyalty comparisons
- **Strategic Insights:** Actionable recommendations for each segment

### **Interactive Analysis**
Interactive Plotly dashboard available in `dashboards/dashboard_interactive.html` for:
- Dynamic filtering by segment
- Drill-down analysis capabilities
- Real-time metric calculations

---

## 🎯 **Business Value**

### **Immediate Benefits**
- **Strategic Customer Prioritization:** Focus resources on highest-value segments
- **Risk Management:** Early identification of problematic accounts
- **Revenue Optimization:** Targeted pricing and service strategies
- **Data-Driven Decisions:** Replace intuition with analytical insights

### **Long-term Value**
- **Foundation for Advanced Analytics:** Churn prediction, dynamic pricing
- **Competitive Advantage:** Sophisticated customer management vs. traditional approaches
- **Scalable Framework:** Adaptable to new products and markets
- **ROI Tracking:** Measurable impact on business metrics

### **Expected ROI**
- **18-25% revenue growth** through optimized customer strategies
- **30-40% improvement** in marketing efficiency
- **20% reduction** in churn for high-value segments

---

## 🔄 **Project Status**

### **Current Phase: Segmentation Complete**
The core segmentation analysis provides immediate actionable insights for customer strategy. The framework is ready for business implementation and continued development.

### **Next Development Phase**
Requires cross-functional collaboration for:
- **CAC Calculation:** Marketing team input for cost allocation
- **LTV Completion:** Comprehensive lifetime value modeling
- **Pilot Implementation:** Testing differentiated strategies

---

## 📄 **License**

This project is for portfolio demonstration purposes. Data has been anonymized and aggregated to protect customer privacy.

---

## 🏆 **Project Outcomes**

This analysis successfully:
- **Identified actionable customer segments** with distinct characteristics
- **Provided scientific foundation** for commercial decision-making
- **Delivered immediate business value** through targeted insights
- **Established framework** for advanced customer analytics

The project bridges technical analysis with business strategy, demonstrating how data science can directly drive revenue growth and operational efficiency in the insurance industry.
