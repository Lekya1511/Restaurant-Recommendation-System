# 🍽️ Restaurant Recommendation System

## Overview

The Restaurant Recommendation System is a Flask-based web application that helps users discover restaurants based on their preferences. The system filters restaurants using factors such as budget, locality, cuisine type, and number of people, then recommends the most suitable dining options.

The project uses restaurant datasets and recommendation techniques to provide personalized suggestions through a simple and interactive web interface.

---

## Problem Statement

Finding a restaurant that matches specific requirements such as budget, location, and cuisine can be time-consuming. This project simplifies the process by automatically filtering and recommending restaurants that best satisfy user preferences.

---

## Features

### User Preference-Based Recommendations
Users can search restaurants by providing:

- Number of people
- Minimum budget
- Maximum budget
- Preferred cuisine
- Preferred locality

### Restaurant Information Display

The system displays:

- Restaurant Name
- Address
- Locality
- Cuisine Type
- Timings
- Rating
- Restaurant URL

### Recommendation Logic

The recommendation engine:

- Filters restaurants according to user preferences.
- Matches cuisine and locality.
- Considers budget constraints.
- Uses similarity-based recommendations when applicable.
- Returns the top matching restaurants.

---

## Technologies Used

### Frontend

- HTML5
- CSS3

### Backend

- Python
- Flask

### Data Processing

- Pandas
- NumPy

### Machine Learning

- Scikit-Learn
- CountVectorizer
- Cosine Similarity

### Dataset

- food1.csv (cleaned restaurant dataset)
- main_rest.csv (restaurant data source)

---

## Project Architecture

### Input Layer

The user enters:

- Number of people
- Budget range
- Cuisine preference
- Preferred locality

### Processing Layer

The backend:

1. Loads restaurant data.
2. Filters restaurants based on locality.
3. Filters according to budget.
4. Filters according to cuisine.
5. Applies recommendation logic.
6. Selects the most relevant restaurants.

### Output Layer

The application displays a list of recommended restaurants along with their details.

---

## Project Structure

```text
Restaurant-Recommendation-System
│
├── app.py
├── requirements.txt
├── Procfile
├── food1.csv
├── main_rest.csv
│
├── templates
│   ├── home.html
│   └── search.html
│
├── static
│   ├── home.css
│   ├── search.css
│   ├── background.jpg
│   └── background1.jpg
│
└── notebook
```

---

## Working of the Recommendation System

### Step 1

The user enters:

- Number of people
- Minimum budget
- Maximum budget
- Cuisine type
- Locality

### Step 2

The system filters restaurants available in the selected locality.

### Step 3

Restaurants are filtered according to the user's budget range.

### Step 4

Restaurants matching the selected cuisine are extracted.

### Step 5

The recommendation engine ranks suitable restaurants.

### Step 6

The top recommendations are displayed on the result page.

---

## Installation and Execution

### Clone the Repository

```bash
git clone https://github.com/Lekya1511/Restaurant-Recommendation-System.git
```

### Move into the Project Directory

```bash
cd Restaurant-Recommendation-System
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

If the above command does not start the server, use:

```bash
flask run
```

### Open in Browser

```text
http://127.0.0.1:5000
```

or

```text
http://localhost:5000
```

---

## Requirements

- Python 3.8 or higher
- Flask
- Pandas
- NumPy
- Scikit-Learn

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## Future Enhancements

- User Authentication
- Personalized User Profiles
- Restaurant Images and Reviews
- Location-Based Recommendations
- Real-Time Restaurant Data Integration
- Advanced Machine Learning Models
- Mobile Responsive Interface

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Flask Web Development
- Recommendation Systems
- Data Processing using Pandas
- Machine Learning Fundamentals
- Frontend and Backend Integration
- Working with Real-World Datasets

---

## Author

### Lekya Dosakayala

B.Tech Computer Science and Engineering

GitHub: https://github.com/Lekya1511

LinkedIn: https://www.linkedin.com/in/lekya-dosakayala-b252b0320/

Email: lekyadosakayala@gmail.com
