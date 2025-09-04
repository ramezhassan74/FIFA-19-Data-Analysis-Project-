# FIFA Data Analysis Project ⚽📊

This project focuses on **data cleaning, preprocessing, and regression modeling** using FIFA players dataset.  
We explore player attributes (Overall, Age, Finishing, Short Passing, Ball Control, Vision, Value, etc.)  
to understand their relationships with market value and performance.

---

## 🚀 Project Workflow
1. **Data Collection**  
   - Import FIFA players dataset from Excel.  
   - Check missing values and handle them with dropna or imputation.  

2. **Data Cleaning**  
   - Standardize columns.  
   - Handle NaN values.  
   - Ensure consistency across features.  

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics with `describe()`.  
   - Visualizations of distributions and correlations.  

4. **Modeling**  
   - Simple Linear Regression.  
   - Polynomial Regression with different degrees.  
   - Comparison of R² and MSE across models.  

5. **Evaluation**  
   - Find the best polynomial degree.  
   - Compare actual vs. predicted player values.  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  

---

## 📊 Results
- Regression models highlight how `Overall` and `Age` affect player `Value`.  
- Higher-degree polynomials may overfit, so model selection is based on balancing R² and MSE.  

---

⬇ **Scroll for Arabic** ⬇  

---

# مشروع تحليل بيانات فيفا ⚽📊

المشروع ده بيهتم بـ **تنظيف البيانات، تجهيزها، وبناء نماذج الانحدار** باستخدام بيانات لاعبي فيفا.  
استكشفنا الخصائص المختلفة للاعبين (Overall, Age, Finishing, Short Passing, Ball Control, Vision, Value ...)  
عشان نفهم علاقتها بقيمة اللاعب السوقية وأداءه.

---

## 🚀 خطوات المشروع
1. **تجميع البيانات**  
   - استيراد ملف بيانات اللاعبين من Excel.  
   - فحص القيم المفقودة والتعامل معاها (dropna أو Imputer).  

2. **تنظيف البيانات**  
   - توحيد الأعمدة.  
   - معالجة القيم الفاضية.  
   - التأكد من تناسق البيانات.  

3. **التحليل الاستكشافي (EDA)**  
   - إحصائيات وصفية باستخدام `describe()`.  
   - رسومات بيانية لتوزيع البيانات والعلاقات.  

4. **النمذجة**  
   - الانحدار الخطي البسيط.  
   - الانحدار المتعدد (Polynomial Regression) بدرجات مختلفة.  
   - مقارنة نتائج R² و MSE بين النماذج.  

5. **التقييم**  
   - اختيار أفضل درجة Polynomial.  
   - مقارنة القيم الفعلية مع القيم المتوقعة.  

---

## 🛠️ الأدوات
- **بايثون**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  

---

## 📊 النتائج
- النماذج وضّحت تأثير الـ `Overall` والـ `Age` على قيمة اللاعب.  
- الدرجات العالية من Polynomial ممكن تؤدي لـ overfitting، عشان كده الاختيار بيعتمد على موازنة R² و MSE.  
