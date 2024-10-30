
# Project:Book Recommendation System Using Machine learning

A machine learning-based desktop application that provides personalized book recommendations. This system utilizes user ratings and book metadata to suggest books that users are likely to enjoy.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Datasets](#datasets)
- [APIs Used](#apis-used)
- [Screenshots](#Screenshots)
- [Installation](#installation)
- [Deployment](#deployment)
- [Usage](#usage)
- [Running Tests](#running-tests)
- [Acknowledgments](#acknowledgments)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

## Description

The Book Recommendation System is designed to help users discover books based on their reading history and preferences. By leveraging collaborative filtering techniques and content-based filtering, the application suggests books similar to those the user has rated highly. The system also provides detailed information about each book, including author, genre, and a brief description, fetched from external APIs.

## Features

- **Personalized Recommendations**: Provides book suggestions tailored to individual preferences.
- **Search Functionality**: Users can search for books by title, author, or genre.
- **Detailed Book Information**: Displays comprehensive details about each recommended book.
- **User Ratings**: Users can rate books, improving the accuracy of future recommendations.

## Datasets

The recommendation system is trained using the following datasets:

- **[GoodBooks-10K Dataset](https://www.kaggle.com/datasets/zygmunt/goodbooks-10k)**: Contains 10,000 books and over 6 million ratings from Goodreads.
- **[Books Dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks)**: A dataset containing information about books, including titles, authors, and genres.
- **[Main Dataset](https://www.kaggle.com/datasets/ra4u12/bookrecommendation)**: This dataset contents comprehensive dataset related to that Project

## APIs Used

This application integrates with various APIs to enhance its functionality:

### 1. Google Books API
- **Purpose**: Fetches detailed book information, including metadata and covers.
- **Documentation**: [Google Books API](https://developers.google.com/books/docs/overview)

### 2. Open Library API
- **Purpose**: Retrieves book metadata, including ISBN, title, author, and subject.
- **Documentation**: [Open Library API](https://openlibrary.org/developers/api)

### 3. Kaggle API
- **Purpose**: Automates the downloading of datasets from Kaggle for model training.
- **Documentation**: [Kaggle API](https://www.kaggle.com/docs/api)



## Screenshots

![Main ](https://github.com/chandrashekhard17/Book-Recommendation-System-Desktop-App/blob/a65e6e7986dd24d9d5697bd673f538b537c391c7/screenshots/download.jpeg)

![Screenshot1](https://github.com/chandrashekhard17/Book-Recommendation-System-Desktop-App/blob/a65e6e7986dd24d9d5697bd673f538b537c391c7/screenshots/Screenshot%20(180).png)

![Screenshot2](https://github.com/chandrashekhard17/Book-Recommendation-System-Desktop-App/blob/a65e6e7986dd24d9d5697bd673f538b537c391c7/screenshots/Screenshot%20(181).png)





## Authors

- [@chandrashekhard17](https://github.com/chandrashekhard17)


## 🚀 About Me
I'm a Data Enthusiasist and i love playing with the Data.



## Demo

To see the Demo 

https://github.com/user-attachments/assets/82eb207e-238f-4362-a6a0-9dc762452fd5

# Hi, I'm Chandrashekhar! 
 👋I'm currently exploring the intersection of machine learning and recommendation systems, working on creating intelligent solutions that enhance user experiences and deliver personalized recommendations.

## Connect With Me

- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/chandrashekhar-d-6681b9269/)
- **Twitter**: [Twitter Handle](https://x.com/Chandra8050266)
- **Email**: [chandrashekhar543@example.com](mailto:chandrashekhard543@example.com)

## Desktop Deployment

### Prerequisites

Before deploying the application as a desktop app, ensure that you have the following installed:

- **Python 3.x**
- **pip** (Python package manager)
- **Git** (for version control, optional)
- **PyInstaller** (for creating executables)

### Steps to Deploy

1. **Clone the Repository**:
   If you haven't already cloned the project repository, do so now:
   ```bash
   git clone  git clone https://github.com/chandrashekhard17/Book-Recommendation-System-Desktop-App.git

   cd Book-Recommendation-System-Desktop-App
   
2. **install requirements**:

  ```bash
  pip install -r requirements.txt
  pip install pyinstaller
  pyinstaller --onefile app.py
  pip install streamlit
  ```

3. **run the application**
  
   ```bash
   streamlit run app.py
  ```

