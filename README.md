# PythonProject_01
This project analyzes video game sales from a 2016 dataset containing 11 variables (7 numerical, 4 categorical). The objective is to transform the data by: comparing the average global sales before and after 2005, creating a new column that categorizes records as “pre-2005” or “post-2005". 
The analysis is performed using **Python**, leveraging **Pandas** and **NumPy** for data manipulation.

## Getting Started

### Prerequisites
To run this project, you need:  
- Python 3.x installed  
- Required libraries: **Pandas, NumPy**

- ### Installing
1. Clone the repository to your local machine:git clone https://github.com/keithokeans/PythonProject_01.git
2. Navigate to the project folder: cd PythonProject_01
3. Install dependencies: pip install pandas numpy

4. ## Running the Test
1. Open the Jupyter Notebook (`Project1_Group5.ipynb`)
2. Run the first cell to import necessary libraries (Pandas, NumPy).
3. Run the second cell to load the dataset (vgsales.csv).
4. The next steps will process the data including filtering video game sales data by year, computing the average sales before and after 2005,
   creating a new column that labels records as “pre-2005” or “post-2005”.
5. Run all cells to complete the analysis.

### Breakdown of Tests
- The script checks whether **average sales before 2005** and **after 2005** are significantly different.  
- A new column is created to classify records into "pre-2005" and "post-2005".  
- Missing or incorrect data is handled in the preprocessing step.

## Deployment
This project is designed for **local execution** in a Jupyter Notebook.

## Author
Keith Owusu  

## License
This project is licensed under the MIT License.

## Acknowledgments
- **Dataset:** 2016 Video Game Sales Data  
- **Libraries Used:** Pandas, NumPy
- **Reference from Course Material**
- **Assistance from coursemates**
