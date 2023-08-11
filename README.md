# Manga-Search

A website for retrieving info about mangas using [DBpedia](https://www.dbpedia.org/) and SPARQL built with jQuery.

Example of a DBpedia page for the manga [One Piece](https://dbpedia.org/page/Naruto)

## Dependency installation

No installation of dependencies needed for this project,it was done in pure HTML-CSS-JS with the help of jQuery.

## Running the project

### From the main page

Just open the html file `index.html` in a browser such as Chrome or Firefox.

We land on the search tool where we can start putting the name of a manga and there will be an autocomplete of mangas present on DBPedia.

We can also instead choose to put keywords such as "One" or "Brother" and the search we will display a list of manga related to the keyword.

We also have advanced options to filter the results:

- Filter by _the name of the author (mangaka)_. You must put the full name of the mangaka for example: _Eiichiro Oda_
- Filter by date of appearance of the manga: We select a precise year and we recover the mangas appeared before this date.
- Filter by type of manga: Several options are available.

From the manga list you can navigate to the manga page or the author's page from the clickable links (their name).

In manga page one can navigate to character page, author page or similar manga page.
