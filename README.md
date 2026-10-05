# ai-job-market-salary-analysis
Statistical analysis and dashboard project analyzing AI job market and salary trends from 2024–2025.
โปรเจกต์สรุปวิเคราะห์แนวโน้มตลาดงานและฐานเงินเดือนสายงาน AI เพื่อดูว่าตำแหน่งไหนกำลังมาแรง เงินเดือนเท่าไหร่ และทักษะแบบไหนที่ตลาดต้องการมากที่สุด

---

# จุดประสงค์
 - ดูภาพรวมเงินเดือนตามตำแหน่ง และระดับประสบการณ์
 - สำรวจทักษะ (Skills) ที่บริษัทส่วนใหญ่กำลังมองหา
 - เปรียบเทียบรูปแบบการทำงาน (Remote / Hybrid / On-site)

---

## ไฟล์ใน Repository
 - AI Job Market Trends and Salary Analysis : รายงานสรุปผลการวิเคราะห์ (Dashboard)
 - final_United States AI Job Market & Salary : วิธีการประมวลผลข้อมูลและวิธีการทำวิจัย (Methodology & Data Pipeline)
 - ai_job_dataset : ไฟล์ข้อมูล (Dataset) ที่ใช้ทำวิเคราะห์

---

## ผลการวิเคราะห์ที่สำคัญ

* **ระดับเงินเดือน:** เงินเดือนเฉลี่ยในสายงาน AI อยู่ที่ประมาณ **$73,416.5 USD/ปี** โดยตำแหน่งที่มีค่าตอบแทนสูงที่สุด คือ **Computer Vision Engineer**
* **ปัจจัยหลักที่มีผลต่อเงินเดือน:** ระดับประสบการณ์ (Experience Level) และขนาดองค์กร (Company Size) มีผลอย่างมากต่อระดับค่าตอบแทน โดยระดับผู้บริหาร (Executive Level) ได้รับค่าตอบแทนสูงที่สุด
* **ผลกระทบจาก Automation Risk:** แม้ความเสี่ยงในการถูกแทนที่ด้วย AI ในภาพรวมจะอยู่ที่ประมาณ **50.44%** แต่ไม่ได้ส่งผลให้เงินเดือนหรือความต้องการแรงงานทักษะ AI/Machine Learning ลดลงอย่างมีนัยสำคัญ

## ประสิทธิภาพของแบบจำลองพยากรณ์ 

แบบจำลองประเมินและพยากรณ์เงินเดือนให้ค่าดรรชนีวัดผลดังนี้:
* **MAPE (Mean Absolute Percentage Error):** 12.34% *(ค่า MAPE < 20% แสดงถึงความแม่นยำในระดับดี)*
* **RMSE (Root Mean Square Error):** $24,677.04
* **MAE (Mean Absolute Error):** $18,207.63

## เครื่องมือที่ใช้ 

* **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn
* **Data Visualization:** Looker Studio, Canva, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 👥 ผู้จัดทำ (Authors)

* นางสาวชนกนันท์ พานทอง (รหัส 67050741)
* นางสาวเพ็ญพิชญา มงคลการ (รหัส 67051039)
* นางสาวสิริพรรณ สงนุ้ย (รหัส 67051205)

---
จัดทำโดย [Chanoknan-P](https://github.com/Chanoknan-P)
