MOVIE INFORMATION PORTAL
=========================
Web Technology - I (2301CS363)
Darshan Institute of Engineering and Technology

PROJECT STRUCTURE
------------------
MovieInformationPortal/
|
|-- index.html            (Home page)
|-- movies.html            (Movie Listing page - includes search/filter/sort)
|-- movie-details.html     (Movie Details page)
|-- favorites.html         (Favorites / Watchlist page)
|-- reviews.html           (Reviews & Ratings page)
|-- contact.html           (Contact / Feedback page)
|
|-- css/
|   `-- style.css          (All styling - to be added in Week 2 & 3)
|
|-- js/
|   |-- movies.js          (Movie data + search/filter/sort/details logic)
|   |-- app.js             (Shared/common JS logic)
|   |-- favorites.js       (Add/remove favorites logic)
|   `-- validation.js      (Form validation logic)
|
|-- images/
|   |-- posters/           (Movie poster images)
|   `-- banners/           (Home page banner images)
|
`-- README.txt             (This file)

CURRENT STAGE: WEEK 1 - HTML STRUCTURE
----------------------------------------
This is the plain HTML structure only (no CSS styling, no JavaScript
functionality yet), as per Week 1 of the project schedule.

All 6 pages are complete with:
- Consistent header, logo and navigation menu
- Semantic HTML5 tags (header, nav, main, section, article, footer)
- Movie card structure (poster, title, genre, year, rating, description)
- Search, filter and sort controls (structure only - logic added in Week 4/5)
- Review form and Contact form with required fields
- IDs and classes already added so JavaScript/DOM code can be
  attached easily in later weeks without changing the HTML structure

NEXT STEPS (as per project schedule)
--------------------------------------
Week 2 : Add CSS styling (fonts, colors, layout, movie cards)
Week 3 : Complete responsive design using media queries
Week 4 : Add movie data using JavaScript arrays/objects + basic validation
Week 5 : Make movie cards, search, filter, sort and details dynamic using DOM
Week 6 : Implement Favorites and Reviews functionality using DOM
Week 7 : Add jQuery based interactivity and effects
Week 8 : Integrate Bootstrap for a responsive, professional UI
