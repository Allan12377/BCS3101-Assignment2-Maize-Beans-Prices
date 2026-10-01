# BCS 3101 Assignment 2 Data Pre processing and EDA Pipeline

**Course:** BCS 3101: Basics of Machine Learning  
**Institution:** Kabale University  
**Academic Year:** 2026/2027  

## Project Title
Predicting Monthly Maize and Beans Prices in Selected Ugandan Markets Using Historical Price and Market Data

## Group Members
| Name | Registration Number |
|------|---------------------|
| AYEN GEOFFREY ALEXANDER | 2024/A/KCS/5102/G/F |
| KUKUNDAKWE SAVIOUS | 2024/A/KCS/4333/F |
| AINEBYONA ALLAN | 2024/A/KCS/1670/F |
| KYOSHABIRE DIANAH | 2024/A/KCS/5188/G/F |
| NIYONSHUTI MERCY | 2025/A/KCS/6117/F |
| ARINDA ELIZABETH | 2024/A/KCS/3099/G/F |
| GUMISIRIZA AMBROSE | 2024/A/KCS/3143/F |

## Folder Structure
```
├── README.md
├── README RUN ORDER.txt
├── BCS3101_Assignment2_Pipeline_Guide.pdf   (lecturer companion guide)
├── notebooks/
│   ├── Notebook 1_2024AKCS5102GF.ipynb
│   ├── Notebook2 - 2024AKCS4333F.ipynb
│   ├── Notebook3 - KYOSHABIRE_DIANAH.ipynb
│   ├── Notebook4 - NIYONSHUTI_MERCY.ipynb
│   ├── Notebook5 ARINDA_ELIZABETH.ipynb
│   ├── Notebook6 - GUMISIRIZA_AMBROSE.ipynb
│   ├── Notebook7 - AINEBYONA_ALLAN.ipynb
│   ├── 09_Model_Training_GROUP.ipynb
│   └── FULL PIPELINE BACKUP BCS3101 Assignment2.ipynb
├── data/
│   ├── uganda_maize_beans_selected_markets.csv
│   └── UGA_RTFP_mkt_2007_2026-08-24.xlsx
├── figures/
│   ├── Cleaning Outlier Boxplots.png
│   ├── EDA Target Boxplots.png
│   ├── Feature Correlation Heatmap.png
│   ├── Feature Scaling Comparison.png
│   ├── Maize and Beans Price Scatter Plot.png
│   ├── Maize Price Outliers by Year.png
│   ├── Observed Price Missingness.png
│   ├── PCA Scree Plot.png
│   ├── Price Correlation Heatmap.png
│   ├── Records by Market.png
│   ├── Target Log Transform.png
│   ├── Target Price Distribution Comparison.png
│   ├── Target Price Histograms.png
│   └── Yearly Average Price Trend.png
└── report/
    └── Ambose.docx
```

## How to Run
1. Open the project in Jupyter and set `notebooks/` as the working directory. The selected-markets CSV and source Excel file are already in that folder.
2. Open `FULL PIPELINE BACKUP BCS3101 Assignment2.ipynb` to run the complete pipeline, or open an individual group notebook.
3. Run all cells from top to bottom (Kernel → Restart & Run All). In Google Colab, upload the selected-markets CSV or source Excel file before running.

## Dataset
Uganda Real-Time Food Prices (RTFP) – World Bank / WFP / FAO.  
Seven markets selected: Market Average, Gulu, Lira, Jinja, Hoima, Busia, Mbarara.

## Notes
- Each group member is responsible for one notebook (see table above).
- The group report follows the exact 7-section structure required by the companion guide.
- All decisions (cleaning, encoding, scaling, PCA, split) are documented inside the notebooks and the report.
