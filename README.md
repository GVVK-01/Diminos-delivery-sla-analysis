# 🍕 Diminos Pizza Delivery SLA Analysis

## 📌 Problem Statement
Kanav owns a Diminos pizza franchise where pizzas must be delivered within **31 minutes**.  
Diminos evaluates store performance using the **95th percentile of delivery time**, which must remain **below 31 minutes**.  
Failure to meet this SLA may result in loss of franchise.

As a freelance data scientist, the objective is to analyze delivery performance, identify SLA risks, and provide actionable recommendations to help Kanav sustain his business.

---

## 🎯 Business Objective
- Evaluate whether the store meets Diminos' SLA
- Identify **risk periods** where delivery delays occur
- Provide **data-driven operational recommendations**

---

## 📊 Key Metric
- **95th Percentile of Delivery Time (minutes)**
- SLA Threshold: **< 31 minutes**

---

## 🧪 Methodology
1. Data Cleaning using business constraints
2. Feature Engineering (delivery time, hour, day)
3. Exploratory Data Analysis (EDA)
4. Percentile-based SLA analysis
5. Time-based risk identification
6. Visualization & insights

---

## ⚠️ Key Insights
- Average delivery time is consistently low (~17–18 minutes)
- SLA compliance depends on **extreme delays**, not averages
- **Tuesday shows the highest SLA risk**
- Certain peak hours approach or exceed the SLA threshold

---

## ✅ Recommendations
- Focus on maintaining **95th percentile < 31 minutes**
- Add delivery capacity on **Tuesdays**
- Monitor SLA **hour-wise**, not just daily averages

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy
- Jupyter Notebook

---

## 📌 Conclusion
Although overall performance is satisfactory, proactive management of high-risk periods—especially Tuesdays—is critical to ensure continued SLA compliance and franchise safety.
