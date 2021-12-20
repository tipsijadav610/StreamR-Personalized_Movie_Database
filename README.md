# StreamR: Personalized Movie Database

SteamR is a dynamic web application that allows users to access basic information about movies, such as casting and ratings. It also allow users to rate movies in addition to displaying popular rating such as IMDb. Users will also be able to create their own personal watchlist.

## Get API key
1. Create an account in [TMDb](https://www.themoviedb.org/) 
2. Go to settings
3. Click on the `API` link from the left hand sidebar.
4. Fill out the necessary details(If prompted for your website URL, simply write "NA" if you don't have one)
5. Once your request is granted, the API key will appear on your API sidebar.

## How to run?
1. Clone the repository: `git clone https://github.com/tipsijadav610/StreamR-Personalized_Movie_Database.git`
2. Go to `./StreamR-Personalized_Movie_Database/src` folder. 
3. Install all the necessary libraries: `pip install -r requirements.txt`
4. Replace **YOUR_API_KEY** in both the places (line no. 23 and 43) of `static/recommend.js` file.
5. Open terminal/command prompt and run: `python main.py`.
6. Open browser and type `http://127.0.0.1:5000/`. 
