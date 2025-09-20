# 🛒 Online Retail RFM Analysis — The Story Behind the Data

## Imagine this:
An online retail store has been running for years, accumulating thousands of transaction records. Yet, the business team is frustrated. They keep asking:

■ **“Who are our loyal customers?”**

■ **“Are we losing buyers over time?”**

■ **“Who spends the most — and are they still with us?”**

■ **“How do we identify risky customers before they churn?”**

These weren’t just academic questions. They were real business problems waiting to be answered.
________________

## 🕵️ Step 1 — Profiling the Raw Data

***When we first opened the dataset, it was messy — like an old, cluttered stockroom. There were:***

*Missing values in critical fields like Customer IDs.*

*Duplicate rows that overstated sales.*

*Negative quantities (returns) that distorted metrics.*
_________________

## At this stage, the business question was:

🤔 *“Can we trust our data enough to analyze customer behavior?”*

✅ **Answer: After carefully profiling, removing duplicates, handling nulls, and filtering out invalid entries, we built a dataset that was clean, consistent, and reliable.**
_____________________

## 🧹 Step 2 — Preparing for RFM

*Once the storehouse was in order, we began crafting the RFM metrics:*

**🗒 Recency (R):** *How recently a customer purchased.*

**🗒 Frequency (F):** *How often they bought.*

**🗒 Monetary (M):** *How much they spent.*
______________________

## The business question here was:

**📝** *“How do we define customer value beyond just total sales?”*

✅ **Answer: By applying the RFM model, we transformed raw sales logs into meaningful signals about customer engagement and loyalty.**
___________________

## 📊 Step 3 — Scoring & Segmentation

**Next came the real magic:** *turning numbers into insights.*

**I've scored customers across R, F, and M using quantiles, then combined these scores into customer segments.**

## The business questions were:

 *“Which customers should we reward and retain?”*
 
 *“Which ones are at risk of leaving?”*
 
 *“Can we identify the high spenders that fuel our revenue?”*

##✅ **Answer: Yes! We discovered patterns such as:**

🤠 **Loyal Champions:** *Low Recency, High Frequency, High Monetary.*

🤑 **Big Spenders:** *High Monetary regardless of Recency.*

😧 **At Risk:** *High Recency, low Frequency.*

😤 **Churned:** *No purchases in a long time.*
___________________________

## **🎨 Step 4 — Visual Storytelling**

### *Numbers alone don’t move business leaders.* **<ins>Visuals do</ins>**.

** I've translated the segments into:

📊 **Bar charts** *showing the share of each classification.*

📈 **Scatter plots** *highlighting outliers and clusters.*

🔥 **Heatmaps** *showing relationships between R, F, and M scores.*

## The business question was:
👉 “How do we communicate these insights clearly to decision-makers?”

✅ **Answer:** *With visuals that made patterns obvious at a glance — so strategy teams could act without diving into the raw data.*
______________

## **🚀 The Impact**

**From a tangled dataset of sales transactions, we built a customer intelligence system.**
**What started as messy logs of invoices turned into actionable answers:**

📍*Who to reward.*

📍*Who to re-engage.*

📍*Who to monitor for churn.*
_______________________

## In short, the project showed how data cleaning + RFM + visualization can transform raw retail logs into a powerful business compass.

### *✨ This isn’t just analysis; it’s the story of how data became insight, and how insight drives action.*
__________________________

📍 Project also uploaded to Google Drive for reference and backup.

  https://drive.google.com/drive/folders/1Eqd0C9uX50m26erFzaCFjwQXAMpSOwGF?usp=sharing
____________________________
➢ Online Retail Customer Segmentation (RFM Analysis) End-to-end data analysis project: cleaning, RFM metric calculation, scoring, and customer segmentation with visual insights. Built using Python (Pandas, Matplotlib, Seaborn).


<div align="center">
<img src="https://github.com/Andrew192100099/Online-Retail-Dataset__Analysis-/blob/main/Images/Online%20Retail.jpg" alt="Titanic Analysis" width="400" height="810">
<img src="https://github.com/Andrew192100099/Online-Retail-Dataset__Analysis-/blob/main/Images/Heatmap%20-%20Distribution%20of%20Recency%E2%80%93Frequency%E2%80%93Monetary.png" alt="Heatmap" width="530" height="830">
</div>

![image alt](https://github.com/Andrew192100099/Online-Retail-Dataset__Analysis-/blob/main/Images/Bar%20Chart%20-%20Customer%20Classification%20Distribution.png)

____________

## **Kaggle:** https://archive.ics.uci.edu/dataset/352/online+retail

