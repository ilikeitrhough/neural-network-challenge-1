# Student Loan Risk Prediction with Deep Learning

## Overview

This project involves building a deep neural network model to predict the likelihood that a student loan applicant will repay their loan. By accurately predicting credit rankings, the company can provide more appropriate interest rates to borrowers, improving both customer satisfaction and financial performance.

## Files

- `student_loans_with_deep_learning.ipynb`: The Jupyter Notebook containing all the code for data preparation, model building, training, evaluation, and discussion.
- `student_loans.keras`: The saved Keras model file of the trained neural network.

## Dependencies

To run this project, you'll need the following:

- **Python 3.x**
- **Jupyter Notebook** or **Google Colab**
- **Python Libraries**:
  - `pandas`
  - `tensorflow`
  - `scikit-learn`
  - `pathlib` (for file paths)

You can install the required libraries using pip:

```bash
pip install pandas tensorflow scikit-learn
```

## Instructions

1. **Clone the Repository**: Clone this repository to your local machine or download the ZIP file.

2. **Install Dependencies**: Ensure all the required Python libraries are installed.

3. **Open the Notebook**: Open `student_loans_with_deep_learning.ipynb` in Jupyter Notebook or upload it to Google Colab.

4. **Run the Notebook**: Execute the cells in the notebook sequentially to perform data preparation, model training, evaluation, and to read the discussion.

## Discussion

**Question 1**: Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

**Answer**:

I would need to collect student information (age, gender, location), academic background (GPA, university, major, interest), financial information (credit, income, loan preferences, and previous loan history). This information allows for personaliztion to meet the individuals needs and provides a risk assesment. It provides a full scope of the information and its relevancy.


**Question 2**: Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

**Answer**:

Content-based filtering would be the chosen method for filtering. Using the attributes of users and items it would make recommendation suitable based on the information provided. Having both student and loan information matched based on the content.

**Question 3**: Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.

**Answer**:

1. **Ethics**: There is an opportunity the system favors one group over another. An unethical bias may result from unfair loan recommendations. This would also open up the possibility of illegal activities.

2. **Security**: Any breach would lead to severe legal consequences if personal and financial information become leaked. Handing sensitive informaiton requires high security measures to be implemented. 

## License

This project is licensed under the MIT License.

## Acknowledgments

- **Dataset**: Provided by the company specializing in student loan refinancing.
- **Libraries**: TensorFlow, Pandas, Scikit-learn.
