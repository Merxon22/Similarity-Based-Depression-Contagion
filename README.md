# Spatial-Depression-Influence

The GitHub repository for the research on  **spatial depression influence**.

### 0. Data Availability
The dataset used in this research is not available to the public. Please contact xxx@xxmail.com for dataset request.

### 1. Environment Setup
- Python=3.10.4
- install required libraries by running ``pip install requirements.txt``
- All codes are run in python jupyter notebook.

### 2. Data Preparation
- Once you retrieve the requuired raw dataset, rename it as ``raw_data.csv`` and put it in the project's directory
- Run the entire ``generate_data.ipynb``. Two files should then be generated in the project folder: ``class_data.csv`` and ``student_data.csv``. They include the Moran's I value necessary for the research.

### 3. Data Analysis
- ``class_level.ipynb`` is responsible for classroom level analysis
- ``individual_level.ipynb`` is responsible for individual level analysis
- ``control_analysis.ipynb`` is responsible for age-controlled analysis
- ``curve.ipynb`` is responsible for second-order characteristic investigation
