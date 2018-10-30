# Welcome to the Liri App!
Welcome to Liri, your virtual assistant! This site can be used to search:
  - A song using Spotify,
  - An artist's next few concert dates using BandsInTown,
  - Or your information on your favorite movie using OMDb!

<br>

## How-to
---
1. To search for a song:
<br>
`node liri.js spotify-this-song '<insert song name>'`
![alt text](images/spotify-this.png)
  * OR by default, if nothing is searched then you will get:
![alt text](images/spotify-this-default.png)


2. To search for tour dates:
<br>
`node liri.js concert-this '<insert artist name>'`
![alt text](images/concert-this.png)


3. To search for movie information:
<br>
`node liri.js movie-this '<insert movie name>'`
![alt text](images/movie-this.png)
  * OR by default, if nothing is searched then you will get:
![alt text](images/movie-this-default.png)


4. To search for whatever is in the random.txt file:
<br>
`node liri.js do-what-it-says`
![alt text](images/do-what-it-says.png)