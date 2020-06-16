# Filmovi
Projekt za fakultet, program u .net razvojnom okruženju koji služi za evidenciju i ocjenjivanje filmova.

Možete si napraviti svoj apikey besplatno te ćete imati 1000 query-a dnevno na raspolaganju.
Ovdje sam stavio i svoj kako bi uštedio vrijeme nekome tko hoće samo pregledati.

Te sam za kraj dodao i nešto screenshot-a završne verzije i početnu skicu iz paint-a xD
Napomena: Ne znam koliko če još baza biti podignuta na serveru jer je to od faksa te se preporučuje napraviti vlastitu.

naziv tablice u bazi sertic_Movies sertic_Users
server: 193.198.57.189
ime baze: DOTNET2019
login: student stu!2019neT

"Title":"Saw",
"Year":"2004",
"Rated":"R",
"Released":"29 Oct 2004",
"Runtime":"103 min",
"Genre":"Horror, Mystery, Thriller",
"Director":"James Wan",
"Writer":"Leigh Whannell, James Wan (story), Leigh Whannell (story)",
"Actors":"Leigh Whannell, Cary Elwes, Danny Glover, Ken Leung",
"Plot":"Two strangers, who awaken in a room with no recollection of how they got there, soon discover they're pawns in a deadly game perpetrated by a notorious serial killer.",
"Language":"English",
"Country":"USA",
"Awards":"8 wins & 10 nominations.",
"Poster":"https://m.media-amazon.com/images/M/MV5BMjE4MDYzNDE1OV5BMl5BanBnXkFtZTcwNDY2OTYwNA@@._V1_SX300.jpg",
"Ratings":[{"Source":"Internet Movie Database","Value":"7.6/10"},{"Source":"Rotten Tomatoes","Value":"49%"},{"Source":"Metacritic","Value":"46/100"}],
"Metascore":"46",
"imdbRating":"7.6",
"imdbVotes":"359,174",
"imdbID":"tt0387564",
"Type":"movie",
"DVD":"15 Feb 2005",
"BoxOffice":"$55,100,000",
"Production":"Lions Gate Films",
"Website":"N/A",
"Response":"True"

moj apikey: 963f9d0a
Please append it to all of your API requests,
OMDb API: http://www.omdbapi.com/?i=tt3896198&apikey=963f9d0a

Napisati program koji služi za evidenciju i cjenjivanje filmova.
Korisnik ima opciju pretražiti film putem "http://www.omdbapi.com/" api-ja nakon cega može iz rezultata pretrage spremiti film u vlastitu bazu sa dodatnom kolonom za vlastitu ocjenu.
Kako bi se za spremljene filmove ažurirala ocjena sa IMDB-a, potrebno je napisati kod koji ce za vec spremljene filmove provjeriti i ažurirati ocjenu kada korisnik klikne na button Refresh.

(+) 1. Napraviti racun (ako treba) i dohvatiti api key
(+) 2. Unutar baze podataka napraviti tablicu "Movies" (MOVIE_ID, TITLE, YEAR, ...)
(-) 3. Napraviti WinForm sa karticom 'Pretraži filmove' koji kreira link
	Npr: http://www.omdbapi.com/?apikey=a6623360&t=shawshan&plot=full
	Key = endpoint, value = http://www.omdbapi.com/
	Key = apikey, value =
	(app.config)

http://www.omdbapi.com/apikey.aspx
https://www.codeproject.com/Questions/1105904/Grab-movie-info-from-OMDB-in-Csharp-please-show-an
https://stackoverflow.com/questions/50425077/return-list-from-json-url-c-sharp

Bonus: neka od ideja za feature bi bilo dodavanje pregleda koliko je ukupno sati potrošeno na gledanje tih filmova koji se nalaze u bazi.
