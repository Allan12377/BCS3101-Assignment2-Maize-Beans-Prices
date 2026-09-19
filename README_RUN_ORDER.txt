================================================================================
BCS 3101 ASSIGNMENT 2 – TESTING PACKAGE
How to run everything in Jupyter (step by step)
================================================================================

PROJECT
  Predicting Monthly Maize and Beans Prices in Selected Ugandan Markets
  Kabale University – Group work

--------------------------------------------------------------------------------
WHAT IS IN THIS FOLDER
--------------------------------------------------------------------------------
  uganda_maize_beans_selected_markets.csv   ← main data file (keep in this folder)
  prediction_results_maize_beans.csv        ← example model predictions (already made)

  01_Notebook1_Data_Loading_AYEN.ipynb
  02_Notebook2_Data_Cleaning_KUKUNDAKWE.ipynb
  03_Notebook3_Integration_Encoding_KYOSHABIRE.ipynb
  04_Notebook4_Scaling_NIYONSHUTI.ipynb
  05_Notebook5_Reduction_Split_ARINDA.ipynb
  06_Notebook6_EDA_GUMISIRIZA.ipynb
  07_Notebook7_Full_Pipeline_ALLAN.ipynb
  08_FULL_PIPELINE_BACKUP.ipynb             ← runs the whole pipeline alone
  09_Model_Training_GROUP.ipynb             ← extra training notebook

--------------------------------------------------------------------------------
HOW TO OPEN IN JUPYTER
--------------------------------------------------------------------------------
1. Download and extract this zip.
2. Open Jupyter Notebook or JupyterLab (or Google Colab).
3. Navigate to this extracted folder.
4. Keep the CSV file in the SAME folder as the notebooks.
   (The notebooks look for: uganda_maize_beans_selected_markets.csv)

--------------------------------------------------------------------------------
RECOMMENDED RUN ORDER
--------------------------------------------------------------------------------

OPTION A – Full group sequence (one notebook after another)
  1. Open 01_Notebook1_... and run all cells (Kernel → Restart & Run All)
  2. Open 02_Notebook2_... and run all cells
  3. Open 03_Notebook3_... and run all cells
  4. Open 04_Notebook4_... and run all cells
  5. Open 05_Notebook5_... and run all cells
  6. Open 06_Notebook6_... and run all cells
  7. Open 07_Notebook7_... and run all cells
  8. (Optional) Open 09_Model_Training_GROUP.ipynb and run all cells

  Note: Some middle notebooks expect intermediate CSV files that earlier
  notebooks would create when run. If a file is missing, use OPTION B.

OPTION B – Safest for testing (recommended)
  1. Open 08_FULL_PIPELINE_BACKUP.ipynb
     → Run all cells. This one is self-contained and covers every stage.
  2. Open 09_Model_Training_GROUP.ipynb
     → Run all cells to train the model and create/update the predictions CSV.
  3. Optionally open any of 01–07 to review that member’s work.

--------------------------------------------------------------------------------
IF A CELL GIVES A FILE-NOT-FOUND ERROR
--------------------------------------------------------------------------------
- Make sure uganda_maize_beans_selected_markets.csv is in the same folder
  as the notebook you are running.
- Or change the path in the cell to the full location of the CSV.
- Notebooks 03 and 04 may look for uganda_maize_beans_encoded.csv or
  uganda_maize_beans_scaled.csv. Those are created only if earlier notebooks
  were run successfully. Use 08_FULL_PIPELINE_BACKUP if you want one file
  that does not depend on intermediate files.

--------------------------------------------------------------------------------
GROUP MEMBERS AND NOTEBOOKS
--------------------------------------------------------------------------------
  01  AYEN GEOFFREY ALEXANDER          2024/A/KCS/5102/G/F
  02  KUKUNDAKWE SAVIOUS               2024/A/KCS/4333/F
  03  KYOSHABIRE DIANAH                2024/A/KCS/5188/G/F
  04  NIYONSHUTI MERCY                 2025/A/KCS/6117/F
  05  ARINDA ELIZABETH                 2024/A/KCS/3099/G/F
  06  GUMISIRIZA AMBROSE               2024/A/KCS/3143/F
  07  AINEBYONA ALLAN                  2024/A/KCS/1670/F
  08  Full pipeline backup (anyone)
  09  Model training (extra group task)

--------------------------------------------------------------------------------
END
================================================================================
