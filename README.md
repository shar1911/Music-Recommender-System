# Music-Recommender-System
The Music Recommender System is a web application designed to provide personalized music recommendations based on user-selected songs. Utilizing the power of machine learning and the extensive music database of Spotify, this system aims to enhance the music discovery experience by suggesting similar tracks that align with the user's taste.

Features
1)User-Friendly Interface: Built with Streamlit, the application offers an intuitive and interactive user interface where users can easily select songs and receive recommendations.
2)Song Selection: Users can type or select a song from a dropdown menu that features a comprehensive list of songs from the dataset.
3)Recommendations Display: Once a song is selected, the system generates and displays up to five recommended songs along with their album covers.
4)Spotify Integration: The application uses the Spotify API to fetch album cover images for the recommended songs, providing a visually appealing and engaging experience.

Technical Details
1)Programming Language: Python
2)Web Framework: Streamlit
3)Machine Learning: Utilizes a pre-trained similarity model to find and recommend songs similar to the selected track.
4)Data Storage: Pickle is used for storing and loading the music dataset and similarity matrix.
5)API Integration: Spotipy, a lightweight Python library for the Spotify Web API, is used to fetch song details and album covers.

How It Works
1)Initialize Spotify Client: The application initializes a Spotify client using provided credentials to access the Spotify API.
2)Select a Song: Users can choose a song from a dropdown menu populated with the available tracks in the dataset.
3)Fetch Recommendations: Upon selecting a song and clicking the "Show Recommendation" button, the system calculates the similarity between the selected song and other songs in the dataset.
4)Display Recommendations: The top five most similar songs are displayed, each accompanied by its album cover fetched from Spotify.

Usage
To use the Music Recommender System:

1)Launch the application.
2)Select a song from the dropdown menu.
3)Click the "Show Recommendation" button.
4)View the recommended songs and their album covers displayed in the columns.
This project serves as an excellent tool for music enthusiasts looking to explore new tracks similar to their favorites. By leveraging machine learning and Spotify's extensive music library, the Music Recommender System provides a seamless and enjoyable music discovery experience.
