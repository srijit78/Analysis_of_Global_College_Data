

# 🎓 College Data Analysis using Python and Tableau-style Visualization

## 📘 Project Overview
This project focuses on exploring and visualizing a large dataset of global colleges to understand how **academic performance, research activity, gender balance, sports participation, and placement success** vary across countries and branches.  
The goal is to identify meaningful trends that explain what makes certain institutions perform better in education, research, and employability.

Using **Python in Google Colab**, this project recreates **interactive, Tableau-style insights** through code and visualization libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🧠 Objectives
1. To study the academic performance (CGPA) of students across various branches.  
2. To analyze placement rates and their variation across different countries.  
3. To explore the relationship between faculty strength and research output.  
4. To examine how factors such as **gender distribution** and **family income** influence performance.  
5. To evaluate the impact of **sports participation** on placement success.  
6. To summarize results and create data-driven insights useful for educational planning and improvement.

---

## 📂 Dataset Description
The dataset used is `College Data.csv`, containing **50,000 records** and the following columns:

| Column Name | Description |
|--------------|-------------|
| Country | Country of the institution |
| Branch | Department or academic branch |
| Total Students | Total number of enrolled students |
| Male | Number of male students |
| Female | Number of female students |
| CGPA | Average CGPA of students |
| Annual Family Income | Average annual income of student families |
| Sports | Type of sport or physical activity offered |
| Research Papers Published | Number of research papers published |
| Placement Rate | Percentage of students placed |
| Faculty Count | Number of teaching staff or faculty members |

---

## 🧩 Tools and Libraries Used
| Category | Tools/Libraries |
|-----------|----------------|
| Programming | **Python (Google Colab)** |
| Data Handling | **Pandas, NumPy** |
| Visualization | **Matplotlib, Seaborn** |
| Data Export | **CSV handling and Google Drive integration** |
| Optional | Tableau (for reference dashboards) |

---

## 📊 Key Visualizations and Analysis
1. **Branch-wise Academic Performance** – Bar chart showing average CGPA across different branches.  
2. **Country vs Placement Rate** – Comparison of placement rates among countries.  
3. **Faculty Count vs Research Output** – Scatter plot revealing the correlation between faculty strength and published research.  
4. **Gender Distribution per Country** – Visualization of male vs female student ratios globally.  
5. **Family Income vs CGPA** – Relationship between financial background and academic achievement.  
6. **Sports Participation Impact** – Study of how sports involvement influences placement success.  
7. **Correlation Heatmap** – Shows relationships among all numeric features.

---

## 🧮 Analytical Insights
- Branches like **Physics** and **Mechanical Engineering** have the highest CGPA averages.  
- Countries such as **Singapore, Japan, and the USA** lead in placement rates.  
- A clear **positive correlation** exists between **faculty count** and **research productivity**.  
- Balanced **gender ratios** are observed in Western countries, while others show slight male dominance.  
- Students from higher-income families often perform marginally better, though effort remains the key factor.  
- Sports participation improves overall placement rates and leadership qualities.

---

## 💾 Exported Results
After analysis, the notebook exports summary tables:
- `Branch_Summary.csv` → Average CGPA, Placement Rate, and Research Papers by branch.  
- `Country_Summary.csv` → Average CGPA, Placement Rate, and Income by country.  

These files can be downloaded or saved directly to Google Drive for future use.

---

## 🚀 How to Run the Project
1. Open the notebook in **Google Colab**.  
2. Upload the dataset `College Data.csv`.  
3. Run each cell sequentially — the notebook is structured from importing data to exporting results.  
4. To save results:
   ```python
   from google.colab import files
   files.download("Branch_Summary.csv")
   files.download("Country_Summary.csv")
   ```
5. Optionally, mount Google Drive to save files permanently:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

---

## 📈 Results Summary
The analysis highlights how **academic, economic, and social factors intertwine** to shape educational success.  
Institutions with strong faculty presence, balanced gender participation, and active sports programs tend to have **better academic results and placement outcomes**.  
This reinforces the idea that **holistic education**—balancing academics, research, and co-curricular engagement—drives institutional excellence.

---

## ✨ Conclusion
This project demonstrates how Python can serve as a **powerful alternative to Tableau** for generating interactive and data-driven visual insights.  
Through this analysis, we transformed raw data into meaningful visual stories, uncovering patterns that connect **students, faculty, and institutional performance** worldwide.

---

## 🙏 Acknowledgement
I would like to thank my faculty mentors and peers for their guidance, and my institution for providing the resources and encouragement to complete this project successfully.

---

## 📧 Author
**Name:** Srijit Das  
**Course:** M.Sc. (Mathematics)  

