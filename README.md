# Movie Guide App

A simple web application that allows users to search for movie information after logging in. The app uses the OMDB API to fetch movie details.

## Features

- User login
- Movie search
- Display movie information including title, rating, runtime, genre, plot, and cast

## Technologies Used

- HTML
- CSS
- JavaScript
- OMDB API

## Setup Instructions

### Prerequisites

- Web browser (e.g., Chrome, Firefox)
- Internet connection

### Steps to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/movie-guide-app.git
   cd movie-guide-app
Open the index.html file:

2. You can simply double-click the index.html file in your file explorer to open it in your default web browser.
Alternatively, you can open it from your code editor (e.g., VS Code) and use the "Open with Live Server" option if available.
Login to the application:

3. Enter the username: user123
Enter the password: password123
Click the "Login" button.
Search for a movie:

4. Enter the movie name in the search input box.
Click the "Search" button.
Movie information will be displayed below the search box.
Files in the Project
index.html: The main HTML file that contains the structure of the web application.
style.css: The CSS file that styles the web application.
script.js: The JavaScript file that contains the logic for login and movie search functionality.
key.js: A placeholder file where you should place your OMDB API key.
OMDB API Key
To use the OMDB API, you need to obtain an API key from OMDB.

5. Sign up and get your API key.
Replace 'YOUR_API_KEY' in script.js with your actual API key.
Example
If you search for "dark knight", the app will display information about the movie "The Dark Knight".

6. Troubleshooting
Invalid Username or Password: Make sure you enter the correct username (user) and password (password).
Movie not found: Ensure you enter the correct movie name. If the movie is not found, it will display a "Movie not found!" message.
API Key Issues: If you encounter issues related to the API key, make sure your API key is correctly placed in the key.js file and it's a valid key.