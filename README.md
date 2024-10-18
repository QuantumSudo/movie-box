Movie-box

Description
Movie Box is a web application built using HTML, CSS, and JavaScript that utilizes the OMDB (Open Movie Database) API to fetch and display movie information. It allows users to search for movies by entering a search term and presents the search results on the webpage.

The application consists of the following components:

HTML: The HTML file contains the structure of the web page. It includes a container element, a heading for the page title, a search input field, a search button, and a container to display the movie results. 
CSS: The CSS file contains the styles that define the appearance of the web page. It applies styles to elements such as the container, heading, search input, search button, and movie result cards. The styles enhance the visual presentation of the application and make it more user-friendly. 
JavaScript: The JavaScript file contains the logic that interacts with the OMDB API and handles user actions. It includes event listeners that respond to user input, such as clicking the search button. The JavaScript code fetches movie data from the OMDB API using the entered search term, processes the response data in JSON format, and dynamically creates HTML elements to display the movie information on the webpage. 
OMDB API: The application utilizes the OMDB API, a free movie database API, to fetch movie data. The API allows users to search for movies based on a search term and provides movie information such as title, year, and poster image. By combining HTML, CSS, JavaScript, and the OMDB API, the Movies Database application provides a user-friendly interface for searching and retrieving movie information, making it a convenient tool for movie enthusiasts and users interested in movie details.

Getting Started
Prerequisites
npm
npm install npm@latest -g

Installation
Get a free API Key at https://https://www.omdbapi.com/apikey.aspx?
Clone the repo
git clone https://github.com/QuantumSudo/movie-box
Install NPM packages
npm install
Enter your API in config.js
const API_KEY = 'ENTER YOUR API';
Change git remote url to avoid accidental pushes to base project
git remote set-url origin github_QuantumSudo/movie-box
git remote -v # confirm the changes

Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)

Contact
Chris Ndegwa - Chriswndegwa@gmail.com

Project Link: https://github.com/QuantumSudo/movie-box

License
Distributed under the MIT License. See LICENSE.txt for more information.
