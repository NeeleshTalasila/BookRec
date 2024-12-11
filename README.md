# BookRec
Book Recommendation System that personalizes recommendations based on individual user preferences and behaviors. The system employs a hybrid approach, combining content-based filtering, collaborative filtering, and user-specific preferences to recommend books that align with a user’s profile. 

No dataset needs to be uploaded, I use synthetic data for my database.

1. To isolate project dependencies, create a virtual environment:
python -m venv venv

2. Activating the Virtual Environment
Activate the virtual environment with the following command:
source ./venv/bin/activate

4. Installing Required Libraries
Install all necessary libraries by running:
pip install pip install pandas numpy scikit-learn surprise faker

5.Running the Prediction Notebook
Open and execute the my_project.ipynb Jupyter Notebook cell by cell to run the code. (run cell 1 first as it will generate the dataset and database, then run the second cell to run the book rec).

