# 🚗 FastTag Vehicle Toll Collection System

A Python-based simulation of an **automated toll collection system** using FastTag-like technology. This notebook demonstrates how vehicles can be identified and charged using simulated tag numbers and balances, implementing basic database logic and user flows.

## 📌 Features

- 🚘 Vehicle Entry & Exit Simulation
- 💳 FastTag Balance Checking
- 🔄 Auto Deduction of Toll Charges
- 📊 Transaction Summary & Logs
- ❌ Rejection of Vehicles with Insufficient Balance
- 🐍 Written entirely in Python using Jupyter Notebook

## 🛠️ Tech Stack

- **Language:** Python
- **Interface:** Jupyter Notebook (`.ipynb`)
- **Libraries Used:**  
  - `pandas` – for structured data storage and manipulation  
  - `datetime` – for timestamping entries/exits  
  - `IPython.display` – for clear output display

## 🚦 Workflow

1. **Vehicle Entry:** Users input vehicle details and FastTag ID.
2. **Balance Verification:** System checks if balance is sufficient.
3. **Toll Deduction:** If valid, toll is deducted and vehicle is allowed to pass.
4. **Transaction Logging:** All transactions are saved in a log for analysis.
5. **Summary Display:** Final transaction summary is shown in tabular format.

## 💻 How to Run

1. Clone the repo or download the notebook:
   ``
   git clone https://github.com/kunalshinde1214/ML-Practice/FastTag.git
   cd FastTag``

2. Open the Notebook:
  ``jupyter notebook FastTag.ipynb``

3. Run the cells step-by-step to simulate toll booth operations.

       File Structure
           FastTag/
        ├── FastTag.ipynb        # Main notebook
        ├── README.md            # Project documentation
        └── .gitignore           # Python and Jupyter ignores

##  📈 Future Improvements

- Integrate with a real-time database (e.g., SQLite or Firebase)
- Add a GUI using Tkinter or Flask for web interface
- Simulate live camera-based FastTag scanning
- Generate toll receipts and export logs as PDF

👨‍💻 Author
Kunal Shinde
GitHub: @kunalshinde1214
   

