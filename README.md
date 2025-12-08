# E-Commerce Store Analysis

A comprehensive data analysis project for an online store operating during **2023**, focusing on understanding performance, customer behavior, product trends, and building a customer classification model using RFM.

---

## 📌 **1. Project Overview**

This project analyzes the performance of an e-commerce store throughout **2023**. The workflow includes data cleaning, exploratory data analysis, customer behavior analysis, RFM segmentation, and building a model to classify customers into value-based categories.

---

## 📊 **2. Dataset Source**

The dataset was obtained from **Kaggle**, then cleaned, processed, and prepared for analysis and machine learning tasks.

<a href = "https://www.kaggle.com/datasets/refiaozturk/e-commerce-sales">

---

## 🧹 **3. Data Cleaning**

During the initial inspection, several columns—such as **age**, **gender**, and **region**—were found to contain conflicting and unreliable values. These columns were **removed entirely** to maintain data integrity.

Cleaning steps included:

* Handling missing values
* Standardizing formats
* Removing contradictory columns
* Creating new features based on customer behavior
<img src="images/cleaned dataset.png">


---

## 🔍 **4. Exploratory Data Analysis (EDA)**

### ● Product Analysis

* Identifying top-selling categories
* Analyzing product trends
* Understanding purchase frequency and patterns

<img src="images/visualizations 1.png">
<img src="images/visualizations 2.png">


### ● Customer Analysis

* Extracting **RFM (Recency, Frequency, Monetary)** metrics
* Segmenting customers based on purchasing behavior
* Preparing data for the classification model
<img src="images/Customers RFM and segmetions.png">
---

## 🤖 **5. Customer Classification Model**

Using the RFM features, a machine learning model was built to classify customers into **four value segments**:

1. High-value customers
2. Medium-value customers
3. Low-value customers
4. At-risk / Lost customers

This segmentation supports effective marketing strategies and personalized targeting.

<img src="images/ML model.png">

---

## 🛠️ **6. Tools & Technologies**

### **Python Libraries**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Openpyxl

### **Machine Learning Models**
* K-means clusters

### **Business Intelligence**

* **Power BI**

  * Main Dashboard
  * Mobile Version Dashboard

---

## 📈 **7. Key Insights**

* **Tech-related products** dominated sales and outperformed all other categories.
* Most purchases occurred **midweek**, as displayed in the dashboard.
* The customer model successfully classified users into **4 distinct value segments**.

---

## 🖼️ **8. Dashboard & Images**

Below are sample visuals from the Power BI dashboard:

### **Main Dashboard Preview**

<img src="images\Products Insights.png">
<img src="images\Customers Insights.png"> 

### **Power BI File**

You can view or download the full interactive dashboard here:
[Click to open the Power BI dashboard]
<a href="dashboard/E-commerce-Analysis.pbix">

---

## 📂 **9. Project Structure**

```
e-commerce-analysis/
│
├── data/                # Raw & cleaned datasets
├── notebooks/           # Data analysis notebooks
├── dashboard/             # Power BI dashboards
├── images/              # Dashboard screenshots
└── README.md
```

---

## ▶️ **10. How to Run****

1. Install required Python libraries (Pandas, NumPy, sklearn, etc.)
2. Run the Jupyter Notebook or Python scripts
3. Open the Power BI file to explore visual insights

---



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
<img src="images/Customers RFM and segmetions.png">
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
