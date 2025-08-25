# Capital Bikeshare Study Project

## Project Overview
This repository contains my revised study project on **Capital Bikeshare data analysis**.
The work was originally developed in Jupyter Notebook and demonstrates the full workflow, from data preprocessing to analysis and results.

**Note on the dataset:**  
The dataset *Capital Bikeshare Locations* was originally published via [opendata.dc.gov](https://opendata.dc.gov/) but is no longer available online.
Therefore, this repository focuses on the code, methodology and documented results.
All analysis results are stored inside the Jupyter Notebook itself.

---

## Environment
- Implemented and tested with **Python 3.9.23**
- Developed in an **Anaconda environment**
- Jupyter Notebook as the main interface

---

## How to Run
1. Clone this repository to your local machine
2. Open the Jupyter Notebook (`.ipynb`) file
3. Run the notebook from start to finish (`Kernel → Restart & Run All`)

### 📦 Library Installation
The **first cell** of the notebook will automatically install all required external libraries.
Make sure to run it before executing the rest of the notebook and restart the Kernel.

```python
# core libs
!pip install --upgrade nbformat pandas holidays plotly

# widget stack (classic notebook compatible)
!pip install "notebook==6.1.5" "widgetsnbextension==3.*" "ipywidgets==7.*" anywidget

# enable widgets in classic Notebook
!jupyter nbextension enable --py widgetsnbextension --sys-prefix
```
---

## Results
- All results, visualizations and conclusions are documented directly inside the Jupyter Notebook
- No additional setup is required to view them


## License

This project is distributed under the **MIT License**.
See the [LICENSE](LICENSE) file for the full text.

© 2025 Saniye Ogul.
