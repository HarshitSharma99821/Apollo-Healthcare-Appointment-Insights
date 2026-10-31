# 🏥 Apollo Healthcare Appointment Insights

### Healthcare Analytics | Patient Attendance | Revenue | Doctor Utilisation

## 1. Project Overview

This project explores hospital appointment data to understand patient attendance, appointment trends, no-show behaviour, revenue-related patterns, and doctor utilisation.

The goal is to use Python-based analysis to identify patterns that can support hospital operations and data-driven decision-making.

## 2. Business Problem

Missed appointments, cancellations, patient waiting time, and appointment management challenges may affect healthcare operations. This project examines the available data to identify patterns related to attendance, payments, and operational performance.

## 3. Project Objectives

- Examine appointment trends over time.
- Compare completed, cancelled, no-show, and scheduled appointments.
- Explore booking patterns associated with no-shows.
- Assess reminder and previous-attendance patterns.
- Analyze revenue-related and payment patterns.
- Explore doctor utilisation, waiting time, consultation duration, and patient satisfaction.

## 4. Dataset Information

The project uses two CSV datasets:

| Dataset | Records | Description |
|---|---:|---|
| Appointments | 75,000 | Hospital appointment records |
| Doctors | 320 | Doctor-related information |

The datasets cover appointment records from 2022 to 2024.

## 5. Project Structure

```text
Apollo-Healthcare-Appointment-Insights/
│
├── Apollo_Healthcare_Appointment_Insights.ipynb
├── apollo_appointments_fact.csv
├── apollo_doctors_dim.csv
└── README.md
```

- **Apollo_Healthcare_Appointment_Insights.ipynb** — Python analysis, data exploration, and visualizations.
- **apollo_appointments_fact.csv** — Appointment dataset.
- **apollo_doctors_dim.csv** — Doctor information dataset.
- **README.md** — Project documentation.

## 6. Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 7. Analysis Performed

- Monthly, quarterly, and year-wise appointment trends.
- Appointment outcome distribution.
- No-show patterns by specialty, city, lead time, appointment type, and booking channel.
- Reminder effectiveness and previous attendance patterns.
- Patient and demographic segmentation.
- Revenue-related and payment analysis.
- Insurance and out-of-pocket payment analysis.
- Doctor utilisation, waiting time, consultation duration, and satisfaction analysis.
- Doctor experience and consultation fee analysis.

## 8. Key Performance Indicators

The notebook reports these overall metrics:

| KPI | Result |
|---|---:|
| Total Appointments | 75,000 |
| Unique Patients | 32,705 |
| Completed Appointments | 55,275 |
| No-Show Appointments | 11,584 |
| Cancelled Appointments | 5,793 |
| Completion Rate | 73.70% |
| No-Show Rate | 15.45% |

Additional findings and visualizations are included in the notebook. Review the analysis cells before presenting conclusions.

## 9. How to Run the Project

1. Place this notebook and both CSV files in the same folder.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Apollo_Healthcare_Appointment_Insights.ipynb`.
5. Run the notebook cells in order.

## 10. Conclusion

This project demonstrates how Python and exploratory data analysis can be used to investigate healthcare appointment trends, attendance patterns, payment behaviour, and operational performance.

The analysis can help identify areas for further investigation and support data-informed discussions about appointment planning and hospital operations.

---

## Author

**[Friend's Name]**  
Aspiring Data Analyst

**Skills:** Add only the tools and skills you can confidently explain.

**LinkedIn:** Add your LinkedIn profile URL.
