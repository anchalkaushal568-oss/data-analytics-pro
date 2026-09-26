# Digital Payments in India

**Student:** Anchal Kaushal  
**Program:** IBM SkillsBuild Data Analytics with AI Internship  
**Project period:** 2016–2025

## Files
1. `AnchalKaushal_Digital_Payments_India.ipynb` - complete Python analysis
2. `AnchalKaushal_Digital_Payments_India_ProjectReport.docx` - project report
3. `requirements.txt` - Python packages used
4. `README.md` - project information and run instructions

## Project overview
This project studies digital-payment activity in India across three payment methods:
- UPI
- IMPS
- Cards

The notebook demonstrates data preparation checks, exploratory charts, correlation analysis and a Random Forest regression model.

## Important data note
The dataset is an **illustrative learning dataset** created for this internship project. It is not an official extract from NPCI, RBI or another commercial/statistical database. The values are used to demonstrate an analytics workflow.

If official data is used in a later version, the original source and definitions should be added to the notebook and report.

## Main observations
- Total digital-payment transactions increase strongly across the project period.
- UPI has the highest transaction volume in the 2025 observations.
- Transaction count and transaction value have a positive association in the constructed data.
- Smartphone penetration and transaction volume also have a positive association in the constructed data.
- The Random Forest model is used as a learning exercise with a separate test set.

## How to run
Open a terminal in the project folder and run:

```bash
pip install -r requirements.txt
jupyter notebook AnchalKaushal_Digital_Payments_India.ipynb
```

The dataset is created inside the notebook, so no separate Excel/CSV file is required.

## Author
Anchal Kaushal
