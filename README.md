# Animal Shelter Data Analysis

This study explores trends in 2019-2023 animal shelter data by combining two datasets: data from Louisville Metro Animal Services and from Sonoma County Animal Services. The study will seek to answer the following questions:

   - How many unique animals were served?
   - How many animals were served multiple times?
   - Which animal species and breeds were most commonly served?
   - What are the most common reasons for animals to be taken to an animal shelter?

Visualizations are provided for the following questions:

   - How did animal intake change from 2019 to 2023?
   - How long do animals typically stay in an animal shelter?
   - What are the most common outcomes for animals in an animal shelter?

Along with exploring the questions above, the Analysis portion also includes "Questions for Further Study" that go beyond the scope of this project but are meant for critical thinking and inspiration for further work. The [Resources Used](https://github.com/jmpurvis0/Capstone-Project/blob/main/Resources%20Used.md) file provides links to the dataset websites, as well as an Articles section showing all articles that helped in the creation of this project.

## Setup Instructions
1. Clone the repo to your machine.
2. Open PowerShell (Windows) or Terminal (Mac) and navigate to the project folder.
3. Create a virtual environment.
    - Type  `python -m venv venv` or `python3 -m venv venv`
4. Activate the virtual environment.
    - Windows:  `venv\Scripts\activate`
    - Mac:  `source venv/bin/activate`
5. Install required packages and dependencies.
   - Type   `pip install -r requirements.txt`
6. Open Jupyter Notebook.
   - Type  `Jupyter Notebook`
7. Navigate to the Jupyter Notebook file (it ends with .ipynb) and run the file.
8. Deactivate the virtual environment.
   - Type `deactivate`

## Project Requirements
This analysis fulfills every requirement for the Capstone Project:
1. Read two data files (CSV).
2. Clean data and perform a pandas merge with two datasets. Calculate new values based on the new data set.
3. Make 3 matplotlib visualizations to display data.
4. Utilize a virtual environment and include instructions in the README on how the user should set one up.
5. Annotate code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md.