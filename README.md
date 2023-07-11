# BingeBox - A Video Streaming Platform

This project is a video streaming platform, similar to Netflix, created using HTML, CSS, and JavaScript. It provides a frontend implementation that allows users to browse and watch movies. The project utilizes the TMDB API to fetch movie data, including details such as title, synopsis, genre, release date, and poster images. The YouTube API is used to retrieve movie trailers, and a trailer play on hover feature has been introduced to enhance the user experience.

## Features

- **Movie Data**: The platform fetches movie data from the TMDB API, providing users with a wide selection of movies to choose from. Each movie includes important details such as title, synopsis, genre, release date, and a poster image.
- **Movie Trailers**: The YouTube API integration allows users to watch movie trailers. By clicking on a movie poster or hovering over it, the trailer will start playing, giving users a preview of the movie.
- **Responsive Design**: The platform is designed to be responsive, ensuring optimal viewing across various devices and screen sizes. Users can enjoy the video streaming experience on desktops, laptops, tablets, and mobile devices.
- **User-friendly Interface**: The interface is intuitive and user-friendly, making it easy for users to navigate through the movie collection, select movies, and watch trailers.

## Tech Stack Used

* HTML
* CSS
* JavaScript
* TMDB API
* YouTube API
  
## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```shell
   git clone https://github.com/HarmlessCoder/BingeBox.git

Alternatively, you can download the project files directly from the repository's GitHub page.

1. Open the project folder in your preferred text editor or IDE.

2. In the HTML file (index.html or similar), locate the API key placeholders for the TMDB and YouTube APIs. Replace them with your own API keys.

3. Save the file and open index.html in your web browser.

4. Browse through the movie collection, and hover over or click on a movie poster to watch the trailer.

5. Enjoy the streaming experience!

## Preview
1. Transparent navbar when showing the banner of a latest trending movie
2. On scrolling the navbar colour changes to black and becomes sticky.
3. Data is dynamic, every time we refresh we will get a new banner of a trending movie.
4. On hovering over a movie, the trailer of that movie will be played via YouTube API.
