<div style="font-family: 'Times New Roman'; font-size: 18px; color: black; line-height: 1.7;">

  <h2 style="text-align: center;">CMSE-202 Macroeconomic Factors</h2>

  <h3>MACROECONOMIC FACTORS & MARKET PERFORMANCE</h3>
  <p><strong>Research Question:</strong> How strongly do macroeconomic factors explain or predict changes in major stock indices over time?</p>

  <h3>Group Members & Contributions</h3>
  <ul>
    <li><strong>Elizabeth Allard</strong> – Responsible for data cleaning and collection, running time-series code and write-up analysis, contributing to the final report.</li>
    <li><strong>Sarah Bejleri</strong> – Responsible for LASSO code analysis, proofreading the final report, and compiling all Jupyter notebooks and the README file.</li>
    <li><strong>Shaurya Arora</strong> – Responsible for NASDAQ and Dow Jones LASSO write-up analysis, and contributing to the project background analysis.</li>
    <li><strong>Joseph Boberg</strong> – Responsible for S&P 500 write-up analysis, writing the conclusion section, and helping compile the README file.</li>
    <li><strong>Ryleigh Bergmann</strong> – Responsible for Multiple Linear Regression write-up analysis and initial project planning documentation.</li>
    <li><strong>Harshita Boddu</strong> – Responsible for writing Multiple Linear Regression code and organizing the GitHub repository.</li>
  </ul>

  <h3>How to Run the Code</h3>

  <h4>FOLDER 1: Project Background</h4>
  <p>
    Contains <code>Project Background.ipynb</code>. This notebook gives an overview of the project question, variables selected, models used, and Python libraries necessary for the analysis. It also includes definitions of all macroeconomic variables and stock market indices. Since this is a predictive modeling project (Multiple Linear Regression, LASSO, Time-Series), we provided intuitive expectations about whether each variable would be positively or negatively correlated with the indices — and why. There is no code to run; everything is written in markdown cells.
  </p>

  <h4>FOLDER 2: Data</h4>
  <p>
    Contains <code>Initial Data Cleaning.ipynb</code>, six macroeconomic CSV files, and one merged dataset: <code>merged_data.csv</code>. Data collection was performed using the <code>yfinance</code> Python library (installable via <code>pip install yfinance</code>). The notebook includes both markdown documentation and five executable code cells, which, when run sequentially, will output the cleaned and merged dataset.
  </p>
  <p>
    <code>merged_data.csv</code> contains macroeconomic variables (CPI, Real Interest Rate, Unemployment Rate, GDP Growth, M2 Money Supply, Federal Funds Rate) and stock market variables (S&P 500, Dow Jones, NASDAQ), reported quarterly (January, April, July, October) from 1992–2023. This dataset is used in all modeling folders that follow.
  </p>

  <h4>FOLDER 3: Multiple Linear Regression</h4>
  <p>
    Contains four notebooks: <code>Multiple Linear Regression Background</code>, <code>S&P 500 Multiple</code>, <code>Dow Jones Multiple</code>, <code>NASDAQ Multiple</code>, and <code>merged_data.csv</code>. Start with the background notebook to learn about OLS statistics (markdown only, no code). Then, run the analysis notebooks for each index. These contain both markdown and code cells. Execute the code cells in order and follow the analysis in markdown cells that explain model results (including two printed model summaries, a correlation matrix, actual vs. predicted plots, and residuals).
  </p>

  <h4>FOLDER 4: LASSO Regression</h4>
  <p>
    Contains four notebooks: <code>Lasso Regression Background</code>, <code>S&P 500 Lasso</code>, <code>Dow Jones Lasso</code>, <code>NASDAQ Lasso</code>, and <code>merged_data.csv</code>. Begin with the background notebook, which provides a markdown explanation of LASSO regression and how it builds on multiple linear regression using regularization. In each index notebook, code and markdown are used to train models, interpret coefficients, and assess accuracy. Each notebook includes four key plots: Actual vs. Predicted, Coefficient Path, and RMSE comparison at different lambda levels.
  </p>

  <h4>FOLDER 5: Time-Series</h4>
  <p>
    Contains four notebooks: <code>Time-Series Background</code>, <code>S&P 500 Time Series</code>, <code>Dow Jones Time Series</code>, <code>NASDAQ Time Series</code>, and <code>merged_data.csv</code>. Begin with the background notebook, which explains first differencing and its use in ARIMA-style LASSO modeling. No code is required here. In the index-specific notebooks, run all code cells in order. Each notebook contains one primary plot — Actual vs. Predicted — and markdown analysis that explains how differencing improves forecasting performance.
  </p>

  <h4>FOLDER 6: Conclusions</h4>
  <p>
    Contains <code>Conclusions.ipynb</code>. This notebook includes only markdown content. We summarized and compared all three models (Multiple Linear Regression, LASSO, Time-Series) across the S&P 500, Dow Jones, and NASDAQ indices. Tables are formatted for clarity and allow for direct comparison of R-squared, RMSE, and variable importance. No code to run — just interpretation and final insights to answer the research question.
  </p>

  <h4>FOLDER 7: Project Planning</h4>
  <p>
    Contains <code>Project Planning.ipynb</code>, which documents the original Gantt chart and team task assignments. Although a few assignments shifted during our time working on the project, the overall workflow remained consistent and organized.
  </p>

  <h4>Final Report.pdf</h4>
  <p>
    This file serves as the Report for the repository and explains the research question, methods, discussion, and conclusions. 
  </p>

  <h4>README.md</h4>
  <p>
    This file serves as the README for the repository and explains how to navigate the project folders, who contributed what, and how to run each notebook in order.
  </p>

</div>