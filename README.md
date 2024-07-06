# Highridge Construction Payment Slip Generator

**Python Version**
--------------

## Description:
---------------
The Highridge Construction Payment Slip Generator is a Python script designed to automate the creation of payment slips for employees of Highridge Construction Company. It generates realistic employee data including names, genders, job titles, and salaries, then assigns employee levels based on predefined salary and gender criteria. Finally, it exports the generated payment slips into a CSV file for further processing.

### Features:
---------
- **Random Data Generation:** Generates random employee data such as names, genders, job titles (Labourer, Engineer, Foreman, Electrician, Plumber, Carpenter), and salaries ranging from 5000 to 35000.
- **Employee Level Assignment:** Assigns employee levels (`A1` and `A5-F`, or `Not disclosed`) based on salary and gender:
  - Employees earning between 10000 and 20000 are assigned `A1`.
  - Female employees earning between 7500 and 30000 are assigned `A5-F`.
  - Others are marked as `Not disclosed`.
- **CSV Export:** Outputs payment slips in CSV format (`highridge_construction_payment_slips.csv`) with columns for Employee Name, Gender, Job Title, Salary, and Employee Level.

### How To Use:
------
1. **Setup:**
   - Ensure Python 3.x is installed on your system.

2. **Dependencies:**
   - Install required libraries using pip:
     ```
     pip install names
	 pip install csv
	 pip install random
     ```

3. **Running the Script:**
   - Open `Module1Assignment_HighridgePaymentSlips.py`.
   - Adjust the `num_workers` variable to set the number of workers to generate.
   - Execute the script:
     ```
     python Module1Assignment_HighridgePaymentSlips.py
     ```

4. **Output:**
   - The generated payment slips will be saved to `highridge_construction_payment_slips.csv` in the same directory.

---


**R Version**
---------

## Description:
------------
The Highridge Construction Payment Slip Generator in R automates the creation of payment slips for employees of Highridge Construction Company. It uses the `randomNames` package to generate employee names and assigns employee levels based on predefined salary and gender criteria. The payment slips are then exported into a CSV file for easy integration with payroll systems.

### Features:
------------
- **Random Data Generation:** Utilizes the `randomNames` package to generate random employee names.
- **Employee Level Assignment:** Assigns employee levels (`A1` and `A5-F`, or `Not disclosed`) based on salary and gender:
  - Employees earning between 10000 and 20000 are assigned `A1`.
  - Female employees earning between 7500 and 30000 are assigned `A5-F`.
  - Others are marked as `Not disclosed`.
- **CSV Export:** Outputs payment slips in CSV format (`highridge_payslip.csv`) with columns for Employee Name, Gender, Job Title, Salary, and Employee Level.

### Usage:
------
1. **Setup:**
   - Ensure R and RStudio are installed on your system.
   - Install required packages:
     ```r
     install.packages("randomNames")
	 install.packages("csv")
     ```

2. **Running the Script:**
   - Open `Module1Assignment_HighridgePaymentSlips.R` in RStudio.
   - Run the script to generate payment slips:
     ```r
     source("Module1Assignment_HighridgePaymentSlips.R")
     ```

3. **Output:**
   - The generated payment slips will be saved to `highridge_payslip.csv` in the working directory.

---

## Files

- `Module1Assignment_HighridgePaymentSlips.py`: Python script to generate payment slips.
- `Module1Assignment_HighridgePaymentSlips.R`: R script to generate payment slips.
- `README.md`: Instructions on how to use the code.