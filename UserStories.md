## User Stories

## Login & Sign Up
* On the top right corner of the page, there should be a signup/login button.
* As a new user, I want to signup for an account so that I can access the feature of the platform.
* As a new user when clicking the signup button for I want to see a modal that pops up in the center of the page that gives me fields to enter a username, email, password, confirm password fields on the form.
* As an existing user when clicking the login button I want to see a modal that pops up in the center of the page that gives me fields to enter my email and password.
* As a user, I want the login/signup process to include password strength requirements and validation to ensure the security of my account. I want errors to show up in red above the form field that is violating the requirements.
* After successful login/sign up, the login/signup button should be replaced with my user icon, and the modal should close and the page should refresh to display the home page.

## Home Page (User)
* After I log in, I want to see all my playlists sorted by last played in a single component in a tile view displaying a clickable playlist image on the home page.
* On the left side of the screen I should see a nav bar with links to "Home" button, "Search" button, "All Tracks", "All Artists", "Liked songs", and a link to each playlist I've created
* When using the search feature I want to be able to search by songs/artist/albums/playlist names in a single search

## Home Page (Artist)
* After I log in, I want to see all my albums sorted by release date in a single component in a tile view displaying a clickable album image on the home page. If I released a single instead of an album, it should be a clickable tile of the single's image.
* On the left side of the screen I should see a nav bar with links to "Home" button, "Search" button, "My Albums", "My Tracks", and "Upload Album"
* When using the search feature I want to be able to search by my songs & albums

## Upload Album/Track Page (Artist)
* Once pressing the 'upload album' button, the artist should be redirected to a form. This form will have the following elements: Album Name, Album Image, Album Type, Track Name(s), Track File(s), Genre
* Once the user presses submit and all form validations pass, the page will redirect to the newly created album's page
* If the form errors, then the page will not redirect but the error messages will populate at under the fields that failed validation

## View All Songs (Artist)
* After pressing 'my tracks', I should be navigated to a page that has a tile view of all my uploaded tracks. These tracks should be able to be deleted once pressed in a modal popup. These tracks can also be updated. The update button and delete button will be two separate buttons, side by side in the modal. The update and delete button's will be in two separate modals.
* The delete button will delete the song upon confirmation, and the page will refresh without the deleted song.
* The update button will load the track page form.

## View All Albums (Artist)
* After pressing 'my albums', I should be navigated to a page that has a tile view of all my albums. Albums can be deleted once pressed in a modal popup.
* Albums can be updated as well, similar to how the 'view all songs' page is set up.

## Playlist Page (User)
* As a user when viewing one of my playlists, I want to see edit (name, image, add songs, delete songs, privacy status) play/pause, shuffle, repeat, sort, and share buttons
* I want to be able to search my playlist for a song/artist
* As a user, I want to see the playlist image, playlist name, number of tracks, total runtime of playlist, and likes
* The playlist tracks will show up as a list view. The individual songs, when hovered, will show a play button, so you can start playing a specific track in the playlist

<!-- ## Artist Page (viewing as user)
* I want to be able to play any song/album on an Artist's page
* i want to be able to follow the artist
* I want to be able to add artist's music (songs or ablums) to one of my playlists
* See artist name, total plays, about section, linked social media accounts section
* See artists top 10 most popular songs
* See Artist Pick playlist
* Discography section w/ popular releases, albums, singles, and EPs (and a show all button) -->

<!-- ## Artist Page (viewing as artist)
* Same a user view, with ability to edit
* view listener stats (stretch goal) -->

## View All Songs (User)
* After pressing 'all tracks', I should be navigated to a page that has a list view of available tracks, sorted in descending order by 'like' count. These tracks should be able to be played, added to a playlist, and/or liked once pressed in a modal popup. All buttons will populate in separate modals.

## View All Albums (User)
* After pressing 'all albums', I should be navigated to a page that has a tile view of all albums. Albums can be pressed, and once pressed, the user will be redirected to the album page.

## Album Page
* As a user, I want to be able to view individual albums in a larger format, with options to like, add to playlist, or share the album with others.
* The album will pop up as a tile on the top with an album synopsis (potential summary) next to it. The tracks in the album will be listed below in a list view. The user can press play on any song, and they can add to playlists and like song(s)

## Music Player
* I want my music player to persist through website navigation on the bottom of the screen (footer like).
* I want to see play/pause, skip, previous, shuffle, repeat buttons

## Likes
* Users should be able to view the likes on a song.
* Users should be able to like a song.
* Users should be able to unlike a song.
* Likes will show when the song is shown in an album page and/or all tracks page.
* POTENTIALLY DO PLAYED COUNT > LIKES (KEEP IN MIND)

<!-- ## Search/Discover page
* I want to have a search bar where i can search for all songs, albums, artists
* I want to have a browse all section where i can see all genres, and then click into each genre too see songs, albums, artists -->
<!-- 
## Bonus: WaveForms
* Users should be able to see the wave forms for a song.
## Bonus: Search
* Users should be able to search for songs by artist or song name.
* Users should be able to view the results of their search. -->
