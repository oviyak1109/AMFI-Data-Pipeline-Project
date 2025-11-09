# AMFI Data Pipeline Project

## Overview
This project demonstrates a complete **data pipeline** that extracts mutual fund data from the **AMFI website**, processes it using **Python**, stores it in **MySQL**, and visualizes insights using **Tableau**.  
The pipeline is designed to automate data collection and provide actionable insights into mutual fund performance.

---

## Tools & Technologies
- **Python** – Data extraction, preprocessing, and automation
- **MySQL** – Database storage and query management
- **Tableau** – Dashboard creation and visualization
- **Excel** – Data exploration and initial cleaning
- **Python Libraries:** `pandas`, `numpy`, `requests`, `sqlalchemy`, `joblib`

---

## Workflow
1. **Data Extraction**
   - Mutual fund data is scraped/downloaded from the AMFI website.

2. **Data Cleaning & Preprocessing**
   - Handle missing values, remove unwanted columns.
   - Optional: stopword removal for text data (if any).

3. **Data Storage**
   - Cleaned data stored in **MySQL** using SQLAlchemy.
   - Automates table creation and insertion.

4. **Visualization**
   - Tableau dashboard created from MySQL data.
   - Visualizes fund categories, performance trends, and comparisons.

5. **Automation**
   - Python scripts can be scheduled to run automatically for updated data.

---

---

## Results
- Built an **end-to-end data pipeline** connecting Python → MySQL → Tableau.  
- Automated cleaning, storage, and dashboard updates.  
- Provided visual insights into mutual fund categories and performance trends.

---

## Future Improvements
- Integrate live AMFI API for daily updates.  
- Deploy the dashboard online using **Tableau Public**.  
- Enhance Python scripts with automated model evaluation for predictions.

---

## Author
**K Oviya**  
Chennai, India  
📧 [k.oviyak9@gmail.com](mailto:k.oviyak9@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/oviya-k-16a383361)
*Note: I used AI tools to assist with debugging and summarizing this README. All project design, implementation, and code logic were done by me.*

## Project Structure
