<h1 align="center">Toxin Analysis in River Systems</h1>
<h3 align="center">Exploring lead, mercury and arsenic levels across national river systems</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
</p>
<h2>Overview</h2>
<p>
An exploratory data analysis (EDA) of the National River Toxin dataset, looking at how levels of lead, mercury and arsenic vary between river systems and over time, and how the measured variables relate to each other.
</p>
<h2>Questions Explored</h2>
<ul>
    <li>Which river systems have the highest average lead levels?</li>
    <li>How have lead levels changed over time in each river system?</li>
    <li>Which variables are correlated with each other?</li>
</ul>
<h2>Methods</h2>
<ul>
    <li><strong>Data cleaning:</strong> filled missing values in numeric columns with the column mean and converted dates to datetime format</li>
    <li><strong>Aggregation:</strong> calculated average toxin levels and ranked river systems by average lead</li>
    <li><strong>Correlation:</strong> built a correlation matrix across all numeric variables</li>
    <li><strong>Visualisation:</strong> bar chart, line graph and correlation heatmap</li>
</ul>
<h2>Key Insights</h2>
<table>
  <thead>
    <tr>
      <th>Finding</th>
      <th>Detail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Most polluted river</strong></td>
      <td>Yangtze has the highest average lead level.</td>
    </tr>
    <tr>
      <td><strong>Trend over time</strong></td>
      <td>There is no clear long term rise or fall in lead levels</td>
    </tr>
    <tr>
      <td><strong>Correlations</strong></td>
      <td>Arsenic and mercury show a fairly strong positive correlation (0.69), meaning they tend to rise and fall together.</td>
    </tr>
  </tbody>
</table>
<h2>Repository Contents</h2>
<ul>
    <li><code>Toxin Analysis in River Systems.ipynb</code>: the full analysis notebook</li>
    <li><code>data/National_River_Toxin_Dataset_1.csv</code>: the dataset</li>
</ul>
<h2>Connect With Me</h2>
<p align="center">
  <a href="https://www.linkedin.com/in/iqra-hussain-aa8029252/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-007ACC?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>
