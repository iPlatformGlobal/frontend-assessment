# Technical assessment for frontend developer

## The purpose of the assessment is to test your ability to:

* Build a single page application using HTML and CSS using responsive design
* Use modern JavaScript efficiently
* Integrate with external APIs

## Please use the following tools as part of your solution:

* ReactJS + Redux
* Typescript (optional)

## What is expected?

This assessment requires you to build a react + redux application to allow an end user to search 
for their favourite artist using the last.fm API and add the artist to a list of favourite artists. 

The app should allow the user to find the releases for a specific artist, 
and add releases to their favourites. Finally, the app should allow the user to view and update their favourites.

> ***Junior developer role*** <br />
> Do not implement the favouriting functionality nor implement the releases functionality mentioned.

#### Optional Extras

The following are completely optional, but will count to your advantage if any are included in the application:

- Requests using the modern `fetch` API
- Async / await statements
- Object spreads
- Functional array methods (map, filter, reduce)
- Unit tests (using jest)

### Artist search

- When the user selects the last.fm link from the navigation bar, 
the site will allow the user to search for their favourite artist. 
- The information is retrieved via AJAX from the last.fm API. 
- The search result from the last.fm API is then displayed in the search results list. 
- From this list the user is able to add an artist to a short list. 
- Once in the short list an arist can be added to the user's favourites.

![last.fm.png](images/lastfm.png)

![Short List](images/shortlist.png)

### Releases for an artist

When the user selects the MusicBrainz link from the navigation bar, the front end will allow the user to search for an artist using the MusicBrainz API. The search results of the search is shown in the search results list. From the search result list, the user can select to see all releases by the artist by clicking on the "show releases" link. When clicking the link, the releases for the corresponding artist will be retrieved from the MusicBrainz API and displayed in the releases list. The following release information is show:

*	Year of release
*	Title of release
*	The label releasing the release
*	Number of tracks on the release
*	Ability to add the release to the user's favourites.

![musicBrianz.png](images/musicbrainz.png)

![Releases](images/releases.png)

### User favourites

- When the user selects the Favourites link from the navigation bar, 
the front end will show the user's favourite artists and releases in two different lists. 
- The user should have the ability to remove artists and releases from their favourites. 
- This information should be stored in Redux. 

> Note: This data **does not need to be persisted to a backend system**.

![Favourites](images/favourites.png)

## Supporting documentation

* The MusicBrainz API is well documented and the information can be found at http://musicbrainz.org/doc/Development/XML_Web_Service/Version_2/Search
* Documentation regarding the last.fm API can be found at http://www.last.fm/api

## What should be part of your solution?

* The solution should be delivered as a collection of source files in a github repository.
* Documentation should be provided in the form of a README file with clear instructions on how to build & run your application.

## How will the technical assessment be evaluated?

* The code will evaluated for clarity, design and readability.

* If any tests are part of the submitted solution, the tests will be run to 
test the solution. The tests will be evaluated to verify the quality of the tests.

* The solution will be opened in the Chrome browser and the functionality 
described above will be tested. Both positive and negative tests 
will be done against the solution.

* Responsive layouts will be simulated using Chrome's developer tools.

## How do I submit my solution?

Create a new repository with your assessment submission on GitHub, and send us the link via email.

> Note: Please do not fork this repository

