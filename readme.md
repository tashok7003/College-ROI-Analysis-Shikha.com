# 🎓 College ROI Analysis: India's Top Engineering, Medical & MBA Colleges

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

A comprehensive Exploratory Data Analysis comparing fees, placements, and Return on Investment (ROI) across India's top colleges to help students make data-driven educational decisions.

## 📊 Project Overview

This project analyzes 300+ top colleges across three major educational streams in India to answer critical questions about educational investments. Using web scraping and data analysis techniques, we provide insights into fees, placement salaries, rankings, and overall value proposition of different educational paths.

## 🚀 Key Insights Discovered

### 💰 Financial Analysis
- **MBA Programs**: Highest median salaries (₹12-18 LPA) but also highest fees (₹15-25 lakhs)
- **Engineering Colleges**: Optimal balance of affordability and ROI with strong placement opportunities
- **Medical Colleges**: Consistent returns with prestigious institutions showing exceptional outcomes

### 🏆 Ranking & Performance
- **IITs and IIMs** dominate both in NIRF rankings and salary outcomes
- **Placement ratings** show strong correlation with actual salary packages
- Several **tier-2 colleges** offer better ROI than some top-tier institutions

### 📈 ROI Findings
- Engineering streams show the most consistent ROI across different college tiers
- MBA from top institutions provides the highest absolute returns
- Medical education offers stable long-term returns despite higher initial investment

## 📁 Project Structure

```
COLLEGE_ROI_ANALYSIS/
│
├── data/
│   ├── raw/
│   │   ├── uncleaned_colleges_dataset.csv    # Original scraped data
│   │   └── uncleaned_colleges_dataset.xls    # Excel format of raw data
│   └── processed/
│       └── cleaned_dataset.csv              # Cleaned and processed data
│
├── analysis/
│   └── college_analysis.ipynb               # Complete Jupyter notebook analysis
│
├── presentation/
│   └── Analysis on Top Indian Colleges.pptx # Project presentation deck
│
├── README.md                                # Project documentation
```

## 🛠️ Technologies Used

- **Programming Language**: Python 3.8+
- **Web Scraping**: BeautifulSoup, Requests
- **Data Analysis**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Notebook Environment**: Jupyter
- **Data Sources**: Shiksha.com

## 📈 Analysis Features

### 1. **Data Collection & Cleaning**
- Automated web scraping from Shiksha.com
- Data cleaning and preprocessing
- Handling missing values and outliers
- Feature engineering for ROI calculations

### 2. **Comparative Analysis**
- Stream-wise fee comparison
- Salary distribution across different college tiers
- Rating analysis (Overall, Placement, Infrastructure)
- NIRF ranking correlation with outcomes

### 3. **ROI & Value Analysis**
- Salary-to-Fee ratio calculations
- Identification of high-ROI institutions
- Affordable excellence colleges
- Investment recommendation frameworks

## 🎯 How to Run This Project

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Required Python packages

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/tashok7003/College-ROI-Analysis.git
cd College-ROI-Analysis
```

2. **Install required packages**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

4. **Open and run the analysis**
   - Navigate to `analysis/college_analysis.ipynb`
   - Run cells sequentially to reproduce the analysis

### Alternative: Quick Setup
```bash
pip install pandas numpy matplotlib seaborn beautifulsoup4 requests jupyter openpyxl
jupyter notebook analysis/college_analysis.ipynb
```

## 📊 Key Visualizations Included

- **Distribution Analysis**: Fees and salary distributions across streams
- **Comparative Charts**: Stream-wise performance comparisons
- **Correlation Studies**: Rankings vs outcomes, ratings vs salaries
- **ROI Metrics**: Return on investment calculations and visualizations

## 🎓 Business Impact

### For Students & Parents
- Make informed college selection decisions
- Understand financial investment returns
- Identify value-for-money institutions

### For Educational Institutes
- Benchmark against competitors
- Identify improvement areas
- Optimize fee structures

## 👤 Author

**Ashok**  
- GitHub: [tashok7003](https://github.com/tashok7003)  
- LinkedIn: [Connect with me](https://linkedin.com/in/ashok--profile/)  
- Email: ashokdevamani7003@gmail.com

## 🙏 Acknowledgments

- **Innomatics Research Labs** for guidance and resources
- **Vishwanath Nyathani, Raghu Ram Aduri, Kanav Bansal, Harsha Mg** for mentorship
- **Shiksha.com** for the data source

## 🔗 Useful Links

- 📊 [View Complete Analysis Notebook](analysis/college_analysis.ipynb)
- 📁 [Access Raw Data](data/raw/)
- 🎥 [Project Presentation](presentation/Analysis%20on%20Top%20Indian%20Colleges.pptx)

---

### 💡 **If this project helps you in making educational decisions, please give it a ⭐!**

*"Data is not just numbers, it's the story of opportunities and choices."*

---

**Last Updated**: Sep 2025  
**Project Status**: ✅ Completed  

This version is clean, well-structured, and professional. It maintains all the important information while being much more readable.

