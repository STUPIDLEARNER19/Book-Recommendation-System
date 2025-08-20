Book Recommendation System
This project is a Book Recommendation System built with Python and Streamlit. It uses collaborative filtering to suggest books and displays the top 50 books from the catalog.

Features
Top 50 Books: Sidebar button to display the most popular books.
Book Recommendation: Select a book and get 5 similar book suggestions.
Data Preview: View the books, users, and ratings data used in the model.
Getting Started
1. Clone the Repository
2. Install Dependencies
Make sure you have Python 3.7+ installed.

pip install streamlit pandas numpy

3. Prepare the Data
Ensure the following files are present in your project directory:

Books.csv
Users.csv
Ratings.csv
popular.pkl
books.pkl
pt.pkl
similarity_scores.pkl
These files are required for the app to run. If you don’t have them, you’ll need to generate them using the notebook provided in the repo.

4. Run the Streamlit App
Use the following command to start the app:

If streamlit is not recognized, use:

The app will open in your browser.

Usage
Top 50 Books: Click the "SHOW" button in the sidebar to view the most popular books.
Book Recommendation: Select a book from the dropdown and click "Recommend Me" to get similar book suggestions.
Data Used: Click "Show" in the sidebar to preview the datasets.
Troubleshooting
Streamlit not recognized: Make sure you installed Streamlit in your current Python environment.
Large files: If you have trouble pushing or pulling large files, use Git LFS.
FileNotFoundError: Ensure all required .csv and .pkl files are in the project directory.
License
This project is for educational purposes.

Install required packages:
 **Book Recommendation System** → [GitHub](https://github.com/STUPIDLEARNER19/Book-Recommendation-System)  
