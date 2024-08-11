
# Movie Recommender System

A web-based Movie Recommendation Engine using Collaborative Filtering with matrix factorization algorithms. Recommendations are based on user similarities: if two users enjoyed similar movies, the system suggests unwatched movies liked by one user to the other.

## Features

### Home Page
The welcoming landing page of the application.

### Recommendation Page 
Presents personalized movie suggestions tailored to each user.

### Rating Page
Enables users to rate and review their watched movies.

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Backend
- Django (Python web framework)

### Machine Learning (Python3)
- NumPy
- Pandas
- SciPy

### Database
SQLite

## Setup and Installation

### Prerequisites
- Python 3.6
- pip3
- virtualenv

### Installation Process

1. Extract the project files to your preferred location.

2. Open a terminal and navigate to the project folder:
   ```
   cd path/to/Movie-Recommender-System
   ```

3. Set up a virtual environment:
   ```
   virtualenv .
   ```

4. Activate the virtual environment:
   - Linux:
     ```
     source bin/activate
     ```
   - Windows:
     ```
     Scripts\activate
     ```

5. Install required packages:
   ```
   pip install -r requirements.txt
   ```

## Launching the Application

1. Go to the main directory:
   ```
   cd main
   ```

2. Initialize the local server:
   ```
   python manage.py runserver
   ```

3. Access the application in your web browser:
   ```
   http://127.0.0.1:8000
   ```

## Final Thoughts

Our Movie Recommender System offers an intuitive platform for movie discovery, leveraging advanced collaborative filtering techniques. We hope this tool enhances your movie-watching experience and helps you uncover new favorites!
