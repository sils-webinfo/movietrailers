This service provides a list of movie-trailers, actors, and subjects. Example data has been added to provide a clearer understanding.

Key:
*all-movie-trailers.html is the entry point to the service. Here one will be able to see a list of 
all movie trailers on the site through a set of outbound links that link to the individual movie trailer page. (URI /movie-trailers)

*all-actors.html is where one will see a set of outbound links that link to the individual actor page. (URI /actors)

*all-subjects.html is where one will see a set of outbound links that link to the individual subject page. (URI /subjects)

*movie-trailer.html is an example of how a particular movie trailer page might look like. Here an example of Lion King was used to demonstrate. 
This page contains outbound links that will connect one back to the list pages for movie-trailers, actors, and subjects. (URI /movie-trailers/{movie-id})

*actors.html is an example of how a particular actor page might look like. This page contains outbound links
This page contains outbound links that will connect one back to the list pages for movie-trailers, actors, and subjects. (URI /actors/{actor/actress-id})

*subjects.html is an example how a particular subject page might look like. This page contains outbound links
This page contains outbound links that will connect one back to the list pages for movie-trailers, actors, and subjects. (URI/subjects/subject/{subject-id})

*timeresult.html is an example of how a page will look like if someone requests a particular time. It will look
almost exactly the same as the movie-trailer individual page, except that the video will start at a specified time. URI (URI/movie-trailers/{movie-id}#t={ms })

*titlesearchresults.html is an example of how the search results might look like if someone searches for a movie-trailer via the title. (URI/titlesearch?titlename={query})

*actorssearchresults.html is an example how the search results might look like if someone searches for an actor/actress by name. (URI/actorsearch?actornamename={query})

*subjectsearchresults.html is an example of how the search results might look like if someone searches by subject name. (URI/subjectsearch?subjectname={query})

*createdresponsemovie.html is an example of what the response might look like when one creates movie-trailer URI.

*createdresponseactor.html is an example of what the response might look like when one creates a new actor resource.

*createdresponsesubject.html is an example of what the response might look like when one creates a subject resource.

*updatedresourcemovie.html is an example of what the response might look like when one updates a movie-trailer.

*updatedresourceactor.html is an example of what the response might look like when one updates an actor resource.

*updatedresourcesubject.html is an example of what the response might look like when one updates a subject resource.




ID Attribute Values
Queries is an id that represents areas (forms) where search queries can be conducted. 
Found in:
* All-movie-trailer page
* All-actors page
* All-subjects page

CreateResource is an id that represents areas were a user can create (POST) a resource. 
Found in:
* All-movie-trailer page
* All-actors page
* All-subjects page

UpdateResource is an id that represents areas were a user can update a resource. 
Found in:
* All-movie-trailer page
* All-actors page
* All-subjects page

See-otherallmovietrailers is an unordered list that contains links to the all-subjects page and actors page.
Found in:
* all-movie-trailer page

See-otherallactors is an unordered list that contains links to the all-subjects page and all-movie-trailer page
Found in:
* all-actors page

See-otherallsubjects is an unordered list that contains links to the all-actors page and all-movie-trailer page
Found in:
* all-subjects page

See-otherall is an unordered list that contains links to the all-actors page, all-movie-trailer page, and all-subjects page.
Found in:
* individual movie-trailer page
* individual actor page
* individual subject page
* Time result page

search-resultsallmovietrailers is an unordered list of links to individual movie-trailer pages.
Found in:
* Title Search Results Page

search-resultsallactors is an unordered list of links to individual actor pages.
Found in:
* Actors Search Results Page

search-resultsallsubjects is an unordered list of links to individual subject pages.
Found in:
* Subjects Search Results Page

Resultsallmovies is an unordered list of links that returns the URI’s of created movie-trailer resources. 
Found in:
* Created Response Movie Page

Resultsallactors is an unordered list of links that returns the URI’s of created actor resources.
Found in:
* Created Response Actor Page

Resultsallsubjects is an unordered list of links that returns the URI’s of created subject resources. 
Found in:
* Created Response Subject Page


Class Attribute Values

Movie-list is an unordered list that contains a list of links to individual movie-trailer pages. 
Found in:
* all-movie-trailer page

Actor-list is an unordered list that contains a list of links to individual actor pages. 
Found in:
* all-actor page
* individual movie trailer page
* Time result page

Subject-list is an unordered list that contains a list of links to individual subjects pages. 
Found in:
* all-subject page
* individual movie trailer page
* Time result page


embed-movielink is a class for an iframe that will be used to embed a movie on an individual movie-trailer page.
Found in:
* individual movie trailer page
* Time result page

synopsis –is a class that is attached to a paragraph element. It provides information about the plot of a movie.
Found in:
* individual movie-trailer page
* Time result page

actorimage –is a class that is attached to an image tag. Images in this class are pictures of the actor. 
* Individual actor page

bio–is a class that is attached to a paragraph element. It provides information about the actor.
Found in:
* individual actor page

actormovielist –is a class attached to an unordered list. This class provides a list of links to movies that the actor has been. 
Found in:
* individual actor page. 

subjectimage –is a class that is attached to an image tag. Images in this class are pictures representing the subject. 
* Individual subject page

description–is a class that is attached to a paragraph element. It provides information about the subject.
Found in:
* individual subject page

subjectmovielist–is a class attached to an unordered list. This class provides a list of links to movies that are related to that subject. 
Found in:
* individual actor page. 

Updatedresponsemovie –is a class attached to a paragraph tag This tag will provide text saying update was a success, along with the movie-title name and id.
Found in:
* Updated Resource Movie page. 

Updatedresponseactor –is a class attached to a paragraph tag This tag will provide text saying update was a success, along with the movie-title name and id.
Found in:
* Updated Resource Actor page. 

Updatedresponsesubject –is a class attached to a paragraph tag This tag will provide text saying update was a success, along with the movie-title name and id.
Found in:
* Updated Resource Subject page. 

Rel Attribute Values
index
Applied to an a tag. A reference to the starting URI for the application.
Found in:
* all-subjects
* all-actors
* Individual movie trailer page
* Individual actor page
* Individual subject page
