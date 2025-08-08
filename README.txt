# How to Run This Project on MacOS

## Prerequisites
- Python 3.8 or higher installed  
  Check by running in Terminal:  
  ```bash
  python3 --version
  ```  

- Jupyter Notebook installed  
  Install it via pip if needed:  
  ```bash
  pip install notebook
  ```

## Steps to Run

1. Open Terminal.

2. Navigate to the project directory where you saved the files:  
   ```bash
   cd /path/to/your/project
   ```

3. Install the required dependencies:  
   ```bash
   pip install duckdb
   ```

4. Make sure the dataset file `dataset.txt` is placed inside a folder named `data` within the project directory:  
   ```
   /your-project-folder/
   ├── Solution.ipynb
   └── data/
       └── dataset.txt
   ```

5. Launch Jupyter Notebook:  
   ```bash
   jupyter notebook Solution.ipynb
   ```

6. Once the notebook opens in your browser, **run all cells from top to bottom**

---

If using VSCode:

Open the project folder in VSCode.
Open Solution.ipynb directly in the VSCode editor.
Make sure the Python extension is installed.
Install the required dependencies:  pip install duckdb
Run cells in order using the notebook interface in VSCode.


If you face any issues, please feel free to reach out!
