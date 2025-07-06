# Portfolio Optimization using Markowitz Efficient Frontier, CML & CAPM

This project demonstrates portfolio optimization using Modern Portfolio Theory (MPT) with real market data. It includes Markowitz Efficient Frontier, Capital Market Line (CML), and Security Market Line (SML) analysis applied to a portfolio of 10 Indian assets over 3 years.



##Assets Used

- Airtel  
- Vodafone  
- Bharat Petroleum  
- IOC  
- JSW Steel  
- Tata Steel  
- SBI  
- HDFC  
- Eicher Motors  
- Mahindra & Mahindra  



### `correctedfrontier.ipynb`
- Constructs the **Efficient Frontier** using matrix-based Markowitz optimization.
- Plots the **Capital Market Line (CML)** from a given risk-free rate.
- Identifies the **Tangency Portfolio** (portfolio with max Sharpe Ratio).
- Displays portfolio weights, risk, and return.

###`combined_index.ipynb`
- Computes a **combined index** as a weighted average of the 10 assets.
- Uses the tangency portfolio weights to generate this index.
- Outputs **expected return** and **risk** (standard deviation) of the combined index.


##Concepts Covered

-  Markowitz Mean-Variance Optimization  
- Efficient Frontier & Minimum Variance Portfolio  
- Capital Market Line (CML) and Tangency Portfolio  
- Sharpe Ratio and Risk-Return Tradeoffs  
- Combined Portfolio Index using optimized weights

---

## How to Use

1. Clone the repository or download the files.
2. Open each `.ipynb` file in **Jupyter Notebook** or **VS Code with Jupyter extension**.
3. Run all cells in order to reproduce the analysis.
4. Make sure `proj_data.xlsx` is in the same folder as the notebooks.

---

## Requirements

Install Python packages (optional but recommended):

```bash
pip install numpy pandas matplotlib openpyxl scipy
