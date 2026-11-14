# PAI-A3-25F-0091

Programming for AI, Assignment 3 (NumPy, Pandas, Matplotlib).

**How to run:** Open `Assignment3_Programming_for_AI.ipynb` in Jupyter or Google Colab. Keep the `data/` folder next to the notebook, because the notebook reads files such as `data/sensor_cube.npy`. Run Kernel > Restart and Run All (in Colab: Runtime > Restart session and run all). The notebook saves `dashboard.png`, `dashboard.pdf` and `wave.gif` in the `outputs/` folder. Only numpy, pandas and matplotlib are used.

**Hardest part:** The weather file had two date formats (YYYY-MM-DD and DD/MM/YYYY), and parsing them without mixing up day and month was the hardest part. I solved it by parsing each format separately with an explicit format string.
