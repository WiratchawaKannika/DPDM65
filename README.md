# DPDM65 
## 🦖 SC 637 802 Data Pre-processing and Data Mining
### กรรณิการ์ วิรัชวา  รหัสนักศึกษา 655020006-1


> # ![image](https://user-images.githubusercontent.com/59467239/176434509-d59b8c23-6b4f-436c-821f-1d9aaaad0f12.png)


![Grading image](grading.png) 


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ✨Table of contents

---


> # Chapter 1. Introduction (บทนำ)

- [x] สรุปเนื้อหา [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/01Intro.jpg) 
  - [ ] Why Data Mining?
  - [ ] Knowledge Discovery (KDD) Process
  - [ ] Data Mining in Business Intelligence
  - [ ] KDD Process: A View from ML and Statistics
  - [ ] Data Mining Functions:
    - (2) Pattern Discovery
    - (3) Classification
    - (4) Cluster Analysis
    - (5) Outlier Analysis
    
- [x] Code
  - [ ] [ทดสอบการใช้งาน Python บน Google Colab](https://github.com/WiratchawaKannika/DPDM65/blob/main/Introduction.ipynb) 


> # Chapter 2. Getting to Know Your Data (ทำความเข้าใจกับข้อมูล)
- [x] สรุปเนื้อหา [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/02Data.jpg) 
  - [ ] Data Objects and Attribute Types
  - [ ] Basic Statistical Descriptions of Data (การอธิบายข้อมูลด้วยสถิติพื้นฐาน)
  - [ ] Data Visualization
  - [ ] Measuring Data Similarity and Dissimilarity (การวัดความคล้ายคลึงและความแตกต่างของข้อมูล)
  
- [x] Code
  - [ ] [1. Basic python](https://github.com/WiratchawaKannika/DPDM65/blob/main/Data101_(Chapter2).ipynb)
    - การตั้งชื่อ Variable (ตัวแปร)
    - ดำเนินการทางคณิตศาสตร์กับตัวแปร
    - การเปลี่ยนชนิดของตัวแปร
    - Check /ตรวจสอบชนิดของตัวแปร
    - Data structure (โครงสร้างข้อมูล)
    - การสร้าง list
    - list slicing
    - Advance list slicing
    - Loop (การให้ com ทำงานที่ซ้ำๆกัน หรือทำงานที่คล้ายๆกันหลายๆรอบ)
    - Nested loop
    - Conditional Statement (if statement)
    - Function
  - [ ] [2. ใช้งานบน pandas/ Visulization](https://github.com/WiratchawaKannika/DPDM65/blob/main/pandas101.ipynb)
    - ขั้นที่ 1 Eyesball the Data 
    - ขั้นที่ 2 Statical deacriptive (ทำความเข้าใจข้อมูลด้วยสถิติพรรณาพื้นฐาน)
    - ชั้นที่ 3.Boxplot เพื่อหาค่าผิดปกติ
    - ขั้นที่ 4 Histogram 
    - ตอบคำถามที่ซับซ้อนขึ้นโดยใช้ Query(indexing)
    - Groupby
    - Data Visulization
      - Simple Line Plots
      - Scatter plot 
      - การใช้ Font ไทยใน matplotlib (Google Colab)
  - [ ] [3. Additional content](https://github.com/WiratchawaKannika/DPDM65/blob/main/Data102_(Chapter2).ipynb)
  
  
> # Chapter 3. Data Preprocessing (การเตรียมข้อมูล)
- [x] สรุปเนื้อหา [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/03Preprocessing.jpg) 
  - Data Cleaning (การทำความสะอาดข้อมูล)
  - Data Integration (การรวมข้อมูลจากหลายแหล่งเข้าด้วยกัน)
  - Data Reduction and Transformation (การลดและการแปลงข้อมูล)
  - Dimensionality Reduction (การลดมิติของข้อมูล)
  
- [x] Code
  - [ ] [preprocessing](https://github.com/WiratchawaKannika/DPDM65/blob/main/preprocessing.ipynb)
    - Data Cleaning
      - Check missing data
      - Dealing with missing data
      - delete records with missing data
      - แทนค่า missing ด้วยค่าที่เหมาะสม (class ใหม่, ที่เราคิดว่าเหมาะสม)
      - แทนที่ missing ด้วยค่า mean รวม
      - แทนที่ missing ด้วยค่า mean ของกลุ่ม
    - การต่อตารางในแนวแกน X (เพิ่ม feature ให้กับ Data)
      - Pandas DataFrame merge 
      - pandas map
    - Smooth data
    - Create pandas df & save pandas df
  
  
> # Chapter 4. Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods (การเตรียมข้อมูล)
- [x] สรุปเนื้อหา [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/06FPBasic.jpg) 
  - [ ] What Is Pattern Discovery?
  - [ ] Pattern Discovery: Why Is It Important?
  - [ ] Basic Concepts: k-Itemsets and Their Supports
  - [ ] Basic Concepts: Frequent Itemsets (Patterns)
  - [ ] From Frequent Itemsets to Association Rules
  - [ ] Limitation of the Support-Confidence Framework
  - [ ] Interestingness Measure: Lift
 
 
> # Chapter 5. Classification 
>> ## Classification: Basic Concepts
- [x] สรุปเนื้อหา [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/08ClassBasic.jpg)
   - [ ] Classification: Model construction from a set of training data
   - [ ] Decision tree induction, Bayes classification methods, linear classifier, ...
   - [ ] Gain Ratio: A Refined Measure for Attribute Selection
   - [ ] Overfitting and Tree Pruning
   - [ ] Classifier Evaluation Metrics: Precision and Recall, and F-measures
   - [ ] Classifier Evaluation: Holdout & Cross-Validation
   
>> ## Classification: Advanced Methods
- [x] สรุปเนื้อหา 1 [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/09ClassAdvanced-1.png)
- [x] สรุปเนื้อหา 2 [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/09ClassAdvanced-2.png)
- [x] สรุปเนื้อหา 3 [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Note/09ClassAdvanced-3.png)
   - [ ] Lazy vs. Eager Learning
   - [ ] Lazy Learner: Instance-Based Methods
   - [ ] The k-Nearest Neighbor Algorithm
   
- [x] Code
  - [ ] [Classification & Cross-Validation](https://github.com/WiratchawaKannika/DPDM65/blob/main/Classification.ipynb)
    - Data Preparation
    - Data Mining เพื่อเตรียมข้อมูลในการทำ Classification
    - Decision Tree (General)
    - ทำ Cross Validation หา Model ที่ดีที่สุด 
      - 1. Decision Tree (Dtree) 
      - 2. K-Neighbors (KNN) 
      - 3. Random Forests 
    
> # Mini Project
- [x] ศึกษางานวิจัที่ได้รับมอบหมาย โดยให้นำเสนอผลงานวิจัย PPT และ Code จาก Git project
  - [ ] Interesting Paper (Project) : [Robust Physical-World Attacks on Deep Learning Visual Classification](https://openaccess.thecvf.com/content_cvpr_2018/html/Eykholt_Robust_Physical-World_Attacks_CVPR_2018_paper)
  - [ ] [Official git](https://github.com/evtimovi/robust_physical_perturbations.git) 
  
- [x] [Code project ที่นำเสนอ](https://github.com/WiratchawaKannika/DPDM65/blob/main/PR2_FRCNN.ipynb)
- [x] PPT นำเสนองานวิจัย [Click Here!](https://github.com/WiratchawaKannika/DPDM65/blob/main/Mini_Project/Paper-Robust%20Physical%20Perturbations(RP2).pdf)

----

     
