# BCS 3101 Assignment 2 – Data Pre-processing & EDA Pipeline

**Course:** BCS 3101: Basics of Machine Learning  
**Institution:** Kabale University  
**Academic Year:** 2025/2026  

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
├── BCS3101_Assignment2_Pipeline_Guide.pdf   (lecturer companion guide)
├── notebooks/
│   ├── 2024AKCS5102GF_BCS3101_Assignment2_Notebook1.ipynb
│   ├── 2024AKCS4333F_BCS3101_Assignment2_Notebook2.ipynb
│   ├── KYOSHABIRE_DIANAH_BCS3101_Assignment2_Notebook3.ipynb
│   ├── NIYONSHUTI_MERCY_BCS3101_Assignment2_Notebook4.ipynb
│   ├── ARINDA_ELIZABETH_BCS3101_Assignment2_Notebook5.ipynb
│   ├── GUMISIRIZA_AMBROSE_BCS3101_Assignment2_Notebook6.ipynb
│   ├── AINEBYONA_ALLAN_BCS3101_Assignment2_Notebook7.ipynb
│   └── FULL_PIPELINE_BACKUP_BCS3101_Assignment2.ipynb
├── data/
│   ├── uganda_maize_beans_selected_markets.csv
│   └── UGA_RTFP_mkt_2007_2026-08-24.xlsx
├── figures/
│   ├── fig1_histograms.png
│   ├── fig2_boxplots.png
│   ├── fig3_heatmap.png
│   ├── fig4_yearly_trend.png
│   ├── fig5_scatter.png
│   └── fig6_missing.png
└── report/
    └── BCS3101_Assignment2_Group_Report.docx
```

## How to Run
1. Place the CSV (or Excel) file in the same folder as the notebook you want to run, or update the path inside the notebook.
2. Open any notebook in Google Colab or Jupyter.
3. Run all cells from top to bottom (Kernel → Restart & Run All).
4. The FULL_PIPELINE_BACKUP notebook runs the entire pipeline in one go.

## Dataset
Uganda Real-Time Food Prices (RTFP) – World Bank / WFP / FAO.  
Seven markets selected: Market Average, Gulu, Lira, Jinja, Hoima, Busia, Mbarara.

## Notes
- Each group member is responsible for one notebook (see table above).
- The group report follows the exact 7-section structure required by the companion guide.
- All decisions (cleaning, encoding, scaling, PCA, split) are documented inside the notebooks and the report.
