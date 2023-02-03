<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Movie Recommendation System</title>
  </head>
  <body>
    <h1>Movie Recommendation System</h1>
    <p>The main goal of this project was to make a recommendation system using a provided data set. The data set consisted of various features like duration, title, language, information about the cast, producer, and budget, etc. The first step was to identify the relevant features, for example, the budget of a movie may not be important to the viewer's interests, but the cast and production may have an impact on whether they would like to watch the movie or not.
    </p>
    <p>
      After cleaning the data, I concatenated the filtered information to create tags, resulting in a single column with all the useful data. Then I vectorized this data, which is a process in which the data is plotted such that similar data will have closer vectors. Finally, I made a function that takes the movie name as input, finds the corresponding vector of that movie on the plot, and returns the names of the five nearest movies as output.
    </p>
    <h2>Technologies Used:</h2>
    <ul>
      <li>Designed a custom model using:
        <ul>
          <li>Pickle</li>
          <li>Pandas</li>
          <li>Numpy</li>
          <li>Requests</li>
        </ul>
      </li>
      <li>Made a web interface using:
        <ul>
          <li>Streamlit</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
      </li>
      <li>Deployed the project using:
        <ul>
          <li>Git</li>
          <li>Github</li>
          <li>Heroku</li>
        </ul>
      </li>
    </ul>
    <p>Check out the deployed project at <a href="https://movie-r-s-z.herokuapp.com/">https://movie-r-s-z.herokuapp.com/</a>!</p>
  </body>
</html>


