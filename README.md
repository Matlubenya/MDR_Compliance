# MDR_Compliance
This project provides automated, data-driven evidence of sterilization process compliance for Medical Device Reprocessing (MDR) facilities.  
It analyzes sterilizer cycle data (from Statim and Ritter units) and produces detailed visual reports demonstrating operational consistency, traceability, and adherence to sterilization parameters.

---

## 🧭 Purpose
To help MDR technicians and auditors rapidly generate objective, visual, and statistical evidence of compliance from daily sterilization logs, ensuring readiness for inspections.

---

## 🧱 Project Architecture
| Component | Description |
|------------|-------------|
| **Python / Jupyter** | Core environment for data processing and visualization |
| **pandas** | Data handling and summary table generation |
| **matplotlib** | Plot generation and result visualization |
| **FPDF / XeLaTeX** | Automated PDF report generation |
| **GitHub** | Version control, documentation, and sharing of evidence |

---

## 📁 Repository Structure
Sterilization-data-analysis/ ├── data/           # Raw Statim and Ritter cycle data ├── processed/      # Clean CSVs from parsed PDFs ├── results/        # Plots and generated compliance reports ├── venv/           # Virtual environment (excluded from Git) ├── notebook.ipynb  # Main Jupyter Notebook ├── README.md └── .gitignore

## ⚙️ Usage
1. Launch Jupyter and open `notebook.ipynb`.  
2. Run the processing cells to extract and clean data.  
3. Generate summary plots and compliance reports (`results/compliance_report.pdf`).  

---

## 🧪 Output
The generated PDF report includes:
- Cover page (title, author, date)
- Summary table
- Visual analysis of sterilization performance (temperature, pressure, efficiency)
- Compliance interpretation and conclusion

---

## ⚖️ Disclaimer
No patient or personal data is used or disclosed in this work. All data is anonymized and strictly limited to equipment performance records.

---

**Author:** Matlub M. Ben Yahya  
**Email:** [matluben@outlook.com](mailto:matluben@outlook.com)  
**Last Updated:** November 2025


