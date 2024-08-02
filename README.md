# Management Of Scientific Data - Exam Project

Exam-Project for the university course "Management of Scientific Data". The task was to come up with a research question, find a suitable dataset, examine, process and analyze the data and perform good data management along the way.
The research question of this project is: Was there a correlation between the positivity rate and number of tests in Germany?

## File Structure

- _*data*_: contains all datasets and respective metadata
  - _*raw_data*_: raw dataset files + metadata + provenance information
  - _*processed_data*_: preprocessed dataset files + metadata
  - _*plots_images*_: plots and images used in the presentation
- _*src*_: contains all the jupyter notebooks used to process the data
  - `src/data_preprocessing.ipynb` generates preprocessed csv files from raw data 
  - `src/data_quality.ipynb` examines data quality on preprocessed dataset
  - `src/data_analysis.ipynb` plots graphs from the preprocessed dataset 
- _*doc*_: contains the project documentation and presentation slides
  - _*installation*_: contains installation information
  - _*DMP*_: contains data management plan and its template
  - _*slides*_: contains the presentation slides

## Getting started

- The execution of the python notebooks requires python version 3.11.9
- It is advisable to create a fresh virtual environment with the packages specified in the file `doc/installation/requirements.txt`
  - This can be done automatically using pip:
    `python3 -m venv .venv`
    `pip install -r requirements.txt`
- It is important to execute the notebook `data_preprocessing.ipynb` first as it creates the data necessary for the other notebooks.

## License

All data is licensed under a [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode.txt) license and all source code is licensed under a non-copyleft [MIT](https://opensource.org/license/mit) license.

## Questions

For further questions or suggestions please contact the repository owner via GitHub([NeWildeSache](https://github.com/User3318)) or mail ([dominic.wild@uni-jena.de])