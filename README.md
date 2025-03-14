# 📊 Software Appliation for Data Science and Analytics (SADSA) Advanced Application  

**SADSA** is a Python-based GUI tool for performing a wide range of statistical and data analysis tasks without writing code. This app allows users to analyze datasets, visualize results, and generate reports in a user-friendly environment.  

---

## 🚀 Features  

- **Interactive GUI** with Tkinter (menu-driven, no coding required).
- Supports **basic and advanced statistical analyses**.
- **Visualization and result export** to text and image formats.
- **Error handling and user prompts** for smooth operation.  
- **Extensible** design to add more statistical methods.  

---

## 📚 Functional Modules  

### 1. **Descriptive Statistics**  
- Summary statistics (Mean, Median, Mode, Std Dev, Min, Max).  
- Distribution plots (Histograms, Boxplots).  

### 2. **Normality Tests**  
- **Univariate**, **Bivariate**, **Multivariate** normality checks.  
- Tests: Shapiro-Wilk, D’Agostino K², Anderson-Darling.  
- Visualizations: Histograms, Q-Q Plots.  

### 3. **Statistical Tests**  
- **Parametric**: T-tests, ANOVA, F-tests.  
- **Non-parametric**: Chi-square, Mann-Whitney U, Wilcoxon, Kruskal-Wallis.  

### 4. **Relations & Associations**  
- **Covariance and Correlation** (Pearson, Spearman, Kendall).  
- **Simple and Multiple Linear Regression**.  
- **ANOVA and MANOVA** for group mean comparisons.  
- **Canonical Correlation Analysis (CCA)**: Analyze relationships between two sets of variables.

### 4. **Exploratory Analysis**  
- **Correspondence Analysis** 
- **Principla Component Analysis**.  
- **Multidimensional Scaling**
- **Exploratory Factor Analysis**
- **Confirmatory Factor Analysis** - including Mediation Analysis

### 4. **Time Series Analysis**  
- **Moving Averages** 
- **Seasonal decomposition/Trend analysis**.  
- **Exponential Smoothing**
- **Holtwinter**

### 4. **Machine Learning**  
- **Logistic Regression** 
- **Support Vector Machines**.  
- **Nearest Neighbors**
- **KNN**
- **Decision Trees**
- **Neural Networks**
- **Random Forests**

### 🧠 **Natural Language Processing (NLP) Functionalities**
- **Text Preprocessing**: Tokenization, Lemmatization, Stop-word removal, Stemming.  
- **Text Mining**: Frequency analysis, Word clouds, N-gram generation (bigrams, trigrams).  
- **Keyword Extraction**: Automatic keyword generation using TF-IDF and RAKE algorithms.  
- **Document Term Matrix**

### 📚 **Bibliometric Analysis Functionalities**
- **Descriptive Bibliometric Statistics**: Number of publications per year, authorship patterns, journal-level analysis.  
- **Co-authorship Network Analysis**: Visualization of author collaboration networks.  
- **Keyword Co-occurrence Analysis**: Identifying and visualizing frequently co-occurring keywords.  
- **Citation Analysis**: Citation count, H-index, G-index calculation for authors, journals, and articles.  
- **Bibliographic Coupling and Co-citation Analysis**: Understanding article and author relationships based on citations.  
- **Thematic Mapping**: Discover research themes and track topic evolution over time.  
- **Trend Analysis**: Identifying emerging trends and declining research areas.  
- **Visualization Tools**: Graphical visualization of bibliometric networks using Matplotlib, Seaborn, NetworkX.  
- **Export Options**: Export data, visualizations, and insights for academic reporting.  

### 🔍 **Meta-Analysis Functionalities**
- **Effect Size Calculation**: Compute standardized mean differences, odds ratios, risk ratios.  
- **Forest Plots**: Visualizing individual study effect sizes and combined effect size.  
- **Funnel Plots**: Detecting publication bias visually.  
- **Heterogeneity Analysis**: Q-test, I² statistic for assessing study variation.  
- **Random and Fixed Effects Models**: Comprehensive meta-analysis modeling.  
- **Moderator Analysis**: Subgroup and meta-regression analysis for moderator effects.  
- **Sensitivity Analysis**: Robustness checks of meta-analysis results.  
- **Publication Bias Tests**: Egger’s test, Begg’s test for bias detection.  
- **Automatic Reporting**: Ready-to-use summary tables, plots, and statistics for publications.  
- **Advanced Integration**: Extensible to network meta-analysis and multi-level meta-analysis.  

📊 **Note**: These functionalities can be accessed via dedicated menus in **SADSA**, such as:
- **"Text Analytics"** for NLP tasks.
- **"Bibliometric Analytics"** for bibliometric studies.
- **"Meta-Analysis"** for systematic reviews and evidence synthesis.

---

## 📈 Output and Reports  

- **Interactive Output Window**:  
  - Left Panel: Statistical results and interpretations.  
  - Right Panel: Corresponding visual plots.  
- **Save Report** button:  
  - **Text reports (.txt)**.  
  - **Graphs (.png)**.  
- User-friendly messages and alerts for selections and errors.  

---

## 📂 Usage  

1. Load dataset (extendable in code).  
2. Use the **menu bar** to select and perform analysis.  
3. View **results and plots** in dynamically generated output windows.  
4. Click **Save Report** to export analysis.  

---

## 🌟 Screenshots  

| Statistical Output  | Plot Visualization  |  
|----------------------|--------------------|  
| ![Output Example](screenshots/output_example.png) | ![Plot Example](screenshots/plot_example.png) |  

---

## 🧩 Extensibility  

- Add new analyses by extending existing methods.  
- Integrate ML algorithms for predictive analytics (future roadmap).  
- Add export to Word/PDF for formal reporting.  

---

## 📜 License  

This project is licensed under **EULA**.  

---

## 📧 Contact  

For queries, suggestions, and collaborations:  
- **Email**: [your.email@example.com](mailto:your.email@example.com)  
- **GitHub**: [github.com/yourusername](https://github.com/yourusername)  
