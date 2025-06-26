# Machine Learning Course Qualification Analysis

📊 Analyzes student performance data to determine qualification for a Machine Learning course based on:
- Total score > 60%
- Each subject score > 60%

## Project Structure
```
Pandas_1/
├── ML_Dataset.csv               # Raw test results dataset
├── pandas_practice.ipynb        # Jupyter Notebook with analysis code
└── students_reports/            # Generated HTML reports
    ├── ST1.html                 # Individual student report
    ├── ST2.html                 # (Reports for ST1-ST8)
    ├── ...
    ├── ST8.html
    └── result.html              # Summary report for all students
```

## How to Use
1. **Prerequisites**:
   - Python 3.x
   - pandas (`pip install pandas`)
   - Jupyter Notebook (`pip install notebook`)

2. **Generate Reports**:
   ```bash
   jupyter notebook pandas_practice.ipynb
   ```
   - Run all cells to generate HTML reports in `students_reports/` folder

3. **View Reports**:
   - Open individual student files (e.g., `ST1.html`) in any browser
   - Check `result.html` for overall qualification summary

## Key Features
- Individual student performance breakdown
- Color-coded qualification status (Green=SELECTED/Red=REJECTED)
- Topic-wise correct/incorrect answers analysis