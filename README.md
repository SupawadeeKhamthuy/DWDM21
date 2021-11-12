# DWDM21
Data Warehouse &amp; Data Mining 2021

นางสาวสุภาวดี คำทุย 623020544-6

กลุ่ม เทเลทับบี้
1. **_นางสาวสุภาวดี คำทุย_**
 
2. นางสาวภัทรสร เทพบุตร

3. นางสาวสุพิชญา ตั้งกิจวานิชย์

4. นางสาวอุมาพร คำภิชัย

5. นางสาวพลอยบงกช แสงโทโพธิ์

 ![Coursework & Grading](DWDM21.jpg)

# สารบัญเนื้อหา

วิชา DATA WAREHOUSE AND DATA MINING (คลังข้อมูลและการทำเหมืองข้อมูล)

* บทที่ 1 [Introduction](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chapter1.pdf)
  * Why Data Mining ? (ทำไมต้องมีการทำเหมืองข้อมูล)
  * What is Data Mining ? (อะไรคือการทำเหมืองข้อมูล)
  * Knowledge Discovery (KDD) Process
  * Data Mining in Business Intelligence 
  * Data Mining (การทำเหมืองข้อมูล)เนื้อหาหลักประกอบด้วย 3 เรื่อง
    * Pattern Discovery (หารูปแบบที่ซ่อนในข้อมูล)
    * Classification (จำแนกข้อมูล)
    * Clustering (จัดกลุ่มข้อมูล)

* บทที่ 2 [Getting to Know Your Data](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chapter2.1.pdf)
  * [Basic Python](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Data101_(Chapter2).ipynb)
    * Variables
    * Casting
    * Data Structure
      * วิธีสร้าง list
    * Loop
      * Nested loop
      * Condition
      * Function
  * [Plot Data](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Data102_(Chapter2).ipynb)
    * Basic Data
    * การใช้ .head() และ .tail()
    * Boxplot
    * Time Series Plot
  * [Visualization](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot
    * Plot
    * Bar chart
    * Histogram
  * [Distance Numpy](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
      * สร้าง numpy array
      * matrix transpose
      * สร้าง matrix เริ่มต้น (zeros,ones)
      * สร้าง matrix random ค่าเเบบมั่วๆ
          * matrix properties
      * Indexing & Slicing ชี้ตัวค่าในเมทริกซ์ยังไง
      * Useful functions
      * วนลูปเอง
          * summation รวมค่าทุกค่าใน array
    * Distance Matrix
      * Euclidean Distance (L2-norm)
      * Distance function
      * Manhattan Distance (L1-norm)
      * Distance of Binary Value
 * บทที่ 3 [Preprocessing](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Data_Preprocessing_(Chapter_3).ipynb) 
   * Meta Data
   * การชี้ข้อมูลในตาราง
     * ชี้แบบธรรมดา
     * ชี้แบบ .iloc[]
   * Missing Value
     * Handling Missing Value 1 (ลบค่า missing)
       * การทำ dropna() ทำให้ข้อมูลหายไป กี่ %
     * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
       * การทำ dropna() แบบเลือก drop เฉพาะ column ที่เราสนใจ (age) ทำให้ข้อมูลหายไป กี่ %
     * Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
     * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
     * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
     * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
   * PANDA
     * Select data by values [PD]
     * ใช้ & (and) และ | (or) ในการรวม list ของ boolean
   * Quiz 4
     * การต่อตารางแนวแกน Y [PD]
     * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
     * การเรียงข้อมูล[PD]
     * utlier
   * Quiz 5
     * Pandas' looping(.iterrows)
   * การรวม 2 ตารางโดยใช้ .merge()
     * Group by (pandas)
     * [PD] save ตารางเอาไปใช้ที่อื่น
     * [PD]การสร้างตาราง
  
  * บทที่ 4 Data Warehousing and On-line Anaalytical Processing
    * Basic Data Warehouse
      * คลังข้อมูลคืออะไร
      * วัตถุประสงค์ และ การบูรณาการ
    * Data Cube and OLAP
      * OLTP & OLAP
      * Data Cubes
      * Conceptual Modeling of Data Warehouse
    * การออกแบบ และการใช้งานคลังข้อมูล
    * ความสำคัญของคลังข้อมูล
   
  * บทที่ 5 [Association_Rules](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
    * Besic Concepts
      * Plot graph of Itemsets
      * Frequence Itemsets to Association Rule
    * Efficient Pattern Mining Methods
      * Apriori
      * Support

  * บทที่ 6 Classification
    * [Desition Tree](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
      * Train Model
      * plot tree
      * Evaluation
      * Random
      * Advanced Tree
      * TEST
    * [KNN](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
      * Split Data
      * Train Model
      * Retrain & Evaluate
      * Neural Network
    * [Evaluation](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
      * Split Data หรือ แบ่ง Data
      * สร้าง Model ทำนาย
      * Evaluation

  * บทที่ 7 [Clustering](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chapter7_Classification_HW.pdf)
    * [Clustering](https://github.com/SupawadeeKhamthuy/DWDM21/blob/main/Chap8_Clustering.ipynb)
      * K-means
      * Generate Data
      * Clustering
      * Example Application (Color Quantization)
      * การนับจำนวนสี
  













