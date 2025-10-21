# Coursera Analysis

## Project Description

`coursera_analysis` is an exploratory data analysis project using Python libraries such as NumPy, Pandas, Matplotlib and Seaborn. The dataset comes from Coursera and contains information on nearly 900 courses. The aim is to identify which organizations and courses dominate in popularity, how certificate type and difficulty relate to enrollments, what factors underpin course success.

### Table of contents in the notebook:
1. Project Setup and Data Acquisition

2. Data Loading and Initial Exploration

    2.1 Data Loading & Initial Exploration

    2.2 Inspect the Structure & Summary Statistics

3. Data Cleaning

    3.1 Check for Missing Values

    3.2 Check for Duplicate Rows

    3.3 Fix Data Types

    3.4 Treating Outliers

4. Exploratory Data Analysis

    4.1 Basic Stats & Structure

    4.2 Inspect Unique Values

    4.3 Leading Courses

    4.4 Difficulty Breakdown

5. Summary & Insights
---
### How to use:
1. Clone the repository

        git clone github.com/TuringCollegeSubmissions/jplesk-DS.v3.1.4.5.git

2. Enter the project folder

        coursera_project
3. Activate your environment

        jupyter notebook
    Then open `Notebooks/coursera_analysis.ipynb` to start analysis.
---
### Data:
- **Source file**: `data/coursea_data.csv`
- **Records**: 891 courses
- **Features**: 7 columns including:
  - 4 categorical: course_title, course_organization, course_Certificate_type, course_difficulty
  - 3 numeric: course_id, course_rating, course_students_enrolled
---
### File Structure:
- coursera_project/ The root directory housing project folders and the main README.

      data/
      notebooks/
      .gitignore
      README.md
      requirements.txt
- data/ Contains the dataset file coursea_data.csv with 891 courses.

        coursea_data.csv
- notebooks/ Holds the interactive analysis notebook (`coursera_analysis.ipynb`), its checkpoint folder (`.ipynb_checkpoints`) and a PDF export (`coursera_analysis.pdf`).

        .ipynb_checkpoints/
        coursera_analysis-checkpoint.ipynb
        Coursera_courses-checkpoint.ipynb

* .gitignore

    Specifies files and folders to exclude from version control (caches, envs, checkpoints, IDE/OS junk, etc.).
* requirements.txt

    Lists the Python dependencies needed to run the project.
* README.md

    Provides the project overview, setup steps, and usage instructions.
---
### Summary of Insights

* **Top Providers**: University of Michigan, Johns Hopkins, UC Irvine, Stanford, Yale, IBM, deeplearning.ai.
* **Top Courses**: Machine Learning (Stanford, 3.2M enrollments), The Science of Well-Being (Yale, 2.5M), Python for Everybody (Michigan, 1.5M).
* **Certificates**: Courses and Specializations dominate. Professional Certificates are rare.
* **Difficulty**: 55% Beginner courses, 22% Intermediate, 21% Mixed, 2% Advanced. Beginner drives ~40M enrollments, Mixed has highest percourse average.

---
### Prerequisites:

* Python 3.8 or higher
* pip (Python package installer)
* Git (to clone the repository)
* Jupyter Notebook or JupyterLab
* Project dependencies (install with pip install -r requirements.txt)

---
### Contributing

Contributions are welcome!

## Author
Created by Jokūbas
