# movies-app-mini-project
####
The Netflix Movie App is a web application that offers a wide range of features for users to discover, watch, and enjoy movies and TV shows. It includes functionalities for user authentication, browsing, searching, and viewing movie details. The application aims to provide an experience similar to the Netflix platform.

Features
Login Route: Allows user authentication, displaying errors for invalid credentials and navigating to the Home Route on success.

Home Route: Displays trending and original movies with loader animations and retry options. Users can click on movies to view details.

Popular Route: Presents a list of popular movies with a loader, retry option, and seamless navigation using the header.

Movie Item Details Route: Displays detailed movie information and similar movies. Features loader animations, retry option, and functional header navigation.

Login Route
Users can log in with a valid username and password. Display error messages when an invalid username or password is provided. Successful login navigates the user to the Home Route. Unauthenticated users trying to access protected routes are redirected to the Login Route. Authenticated users trying to access the Login Route are redirected to the Home Route.

Home Route
Authenticated users see a random movie title and poster with details from the Originals API. Display movies from the Trending Now Movies API and the Originals API. Show loader while fetching data. Users can click on a movie item to navigate to the Movie Item Details Route. If any API request fails, display the corresponding failure view. Users can click "Try Again" to retry the failed request.

Header
Clicking on the Movies logo in the header navigates to the Home Route. Links for Home, Popular, Search, and Account allow users to navigate to their respective routes.

Popular Route
Authenticated users can view a list of popular movies. Display loader while fetching data. Users can click on a movie item to navigate to the Movie Item Details Route. If the API request fails, show the failure view. Users can click "Try Again" to retry the request.

Movie Item Details Route
Authenticated users can see details of a movie. Display loader while fetching data. Show movie details and a list of similar movies. If the API request fails, display the failure view. Users can click "Try Again" to retry the request.

Search Route
Authenticated users can search for movies using a search input and button. Make an API request to search for movies based on the search input. Display loader while fetching search results. Show search results or a "no results" view if the list is empty. Users can click on a movie item to navigate to the Movie Item Details Route.

Account Route
Display the username provided during login. Mask the displayed password. Users can log out by clicking the "Logout" button.

Not Found Route
When a random URL is provided, users are directed to the Not Found Route.

Responsiveness
Ensure the website is responsive for mobile and tablet views.

Quick Tips
Use the provided URLs for data fetch. Use media queries for responsiveness. Avoid using third-party packages not mentioned in the Quick Tips. Style components with normal HTML elements for Mini Projects (styled-components are not supported). Use the testid attribute for HTML elements, following the given examples.

Routes
Render components for different routes as specified. Use the loader container for displaying the loader.

Additional Information
Utilize alt attributes in image elements. Set and access cookies with the key name jwt_token.

Stretch Goals
If you wish to add extra functionality to the project, consider implementing the following features:

Fetch data from the Top Rated Movies API. Enable pagination for popular movies and search results.

These stretch goals are optional but can enhance the application's capabilities.

Resources
Use the provided Data fetch URLs. Refer to the provided user credentials for testing.
