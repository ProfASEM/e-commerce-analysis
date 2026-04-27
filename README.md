# 🛒 E-Commerce Store Analysis

Comprehensive Data Analysis • RFM Segmentation • Machine Learning • Power BI Dashboard

## 1. Project Overview

This project analyzes the performance of an e-commerce store during 2023.
It covers data cleaning, exploratory analysis, customer profiling, RFM segmentation, and building a machine learning model to classify customers.

The project follows a complete end-to-end analytics workflow used in real e-commerce environments.

## 2. Dataset Source

Dataset from Kaggle:
https://www.kaggle.com/datasets/refiaozturk/e-commerce-sales

The data was cleaned, processed, and prepared for analysis and ML tasks.

## 3. Data Cleaning

During initial inspection, several fields such as age, gender, and region contained unrealistic or contradictory values.
These columns were entirely removed to ensure data integrity.

Cleaning steps included:

#### Handling missing values

#### Removing inconsistent columns

#### Standardizing data types

#### Filtering unreliable rows

#### Creating RFM features

<img src="images/clenead dataset.png">

## 4. Exploratory Data Analysis (EDA)

#### Product Insights

Top-selling categories

Revenue patterns

Frequency of purchases

Trend analysis

<img src="images/visualizations 1.png"> <img src="images/visualizations 2.png">

#### Customer Insights (RFM)

RFM metrics were calculated:

**Recency** – how recently the customer purchased

**Frequency** – how often they buy

**Monetary** – how much they spend

These were used for segmentation and ML modeling.

<img src="images/Customer RFM and segmetions.png">

## 5. Customer Classification Model

A machine learning model was built using RFM data to classify customers into:

#### High-value customers

#### Medium-value customers

#### Low-value customers

#### At-risk / Lost customers

Algorithm used:

#### K-Means Clustering

<img src="images/ML model.png">

This segmentation supports targeting strategies and customer retention planning.

## 6. Tools & Technologies
### Python

### Pandas

### NumPy

### Matplotlib

### Seaborn

### Scikit-learn

### Openpyxl

### Business Intelligence

### Power BI (Desktop + Mobile Layouts)

### Machine Learning

### K-Means Clustering

### Feature Scaling

## 7. Key Insights

-Technology products dominated 2023 sales.

-Sales peaked midweek based on dashboard KPIs.

-Customer segmentation revealed 4 distinct clusters.

-High-value customers are responsible for a large share of revenue.

A considerable portion of customers are at-risk and need engagement strategies.

## 8. Dashboard & Visuals
Main Dashboard
<img src="images/Products Insights.png"> <img src="images/Customers Insights.png">
Power BI File

Interactive dashboard (.pbix):
dashboard/E-commerce-Analysis.pbix

## 9. Project Structure
e-commerce-analysis/<br>
│<br>
├── data/ <br>               # Raw and cleaned datasets
├── notebooks/<br>           # Jupyter notebooks (EDA + ML)
├── dashboard/    <br>       # Power BI dashboards
├── images/           <br>   # Screenshots used in README
└── README.md<br>

## 10. How to Run

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn openpyxl


Run the Jupyter Notebook inside the notebooks/ folder.

Open the Power BI file in the dashboard/ folder.

### Contact

LinkedIn: https://www.linkedin.com/in/asem-haij-9797562a8

# تحليل متجر للتجارة الإلكترونية

مشروع متكامل لتحليل بيانات متجر يعمل بالتجارة الإلكترونية خلال عام **2023**، ويهدف إلى فهم الأداء العام، تحليل سلوك العملاء، دراسة اتجاهات المنتجات، وبناء نموذج لتصنيف العملاء باستخدام RFM.

---

## 📌 **1. وصف المشروع**

يحلل هذا المشروع أداء متجر إلكتروني خلال عام **2023**، ويشمل تنظيف البيانات، إجراء تحليلات استكشافية، تحليل المنتجات والعملاء، استخراج RFM، وبناء نموذج لتصنيف العملاء حسب قيمتهم.

---

## 📊 **2. مصدر البيانات**

تم الحصول على البيانات من منصة **Kaggle**، ثم تمت معالجتها وتنظيفها وتجهيزها للتحليل والنمذجة.

<a href = "https://www.kaggle.com/datasets/refiaozturk/e-commerce-sales">
---

## 🧹 **3. تنظيف البيانات**

عند مراجعة البيانات، وُجد أن بعض الأعمدة مثل: **العمر، الجنس، المنطقة** تحتوي على قيم متضاربة، لذلك تم **استبعادها بالكامل** لأنها كانت تضر دقة التحليل.

تضمن التنظيف أيضًا:

* معالجة القيم المفقودة
* توحيد الصيغ
* إزالة الأعمدة غير الدقيقة
* إنشاء أعمدة مشتقة من سلوك العملاء
<img src="images/cleaned dataset.png">
---

## 🔍 **4. التحليل الاستكشافي**

### ● تحليل المنتجات

* تحديد المنتجات والفئات الأكثر مبيعًا
* دراسة اتجاهات المبيعات
* تحليل تكرار الشراء

<img src="images/visualizations 1.png">
<img src="images/visualizations 2.png">
### ● تحليل العملاء

* استخراج قيم **RFM**
* تقسيم العملاء بناء على سلوك الشراء
* تجهيز البيانات للنموذج
<img src="images/Customer RFM and segmetions.png">
---

## 🤖 **5. نموذج تصنيف العملاء**

بناء نموذج يعتمد على ميزات RFM لتقسيم العملاء إلى **4 فئات**:

1. عملاء ذوو قيمة عالية
2. عملاء متوسطو القيمة
3. عملاء منخفضو القيمة
4. عملاء على وشك المغادرة أو مفقودون

هذا يساعد في اتخاذ قرارات تسويقية أكثر دقة.
<img src="images/ML model.png">
---

## 🛠️ **6. التقنيات المستخدمة**

### **بايثون**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Openpyxl

* ### **Machine Learning Models**
* K-means clusters


### **Power BI**

* لوحة رئيسية
* نسخة خاصة بالجوال

---

## 📈 **7. أهم النتائج**

* سيطرة **قطاع التقنية** على المبيعات مقارنة ببقية المنتجات.
* معظم عمليات البيع تتم **في وسط الأسبوع** كما هو ظاهر في لوحات التحكم.
* تم تصنيف العملاء إلى **4 فئات واضحة** تساعد على فهم قيمتهم.

---

## 📂 **8. هيكل المستودع**

```
e-commerce-analysis/
│
├── data/                # البيانات الخام والمنظفة
├── notebooks/           # دفاتر التحليل
├── dashboard/             # ملفات Power BI
├── images/              # صور الداشبورد
└── README.md
```

---

## 📂 **Power BI مرئيات**

<img src="images\Products Insights.png">
<img src="images\Customers Insights.png"> 

تستطيع تحميل ملف dashboard عن طريق الرابط أدناه

<a href="dashboard/E-commerce-Analysis.pbix">


## ▶️ **9. كيفية التشغيل**

1. تثبيت مكتبات Python اللازمة
2. تشغيل الأكواد أو دفاتر Jupyter
3. فتح ملف Power BI لاستعراض التحليل البصري

---

**شكراً لاهتمامك!**
