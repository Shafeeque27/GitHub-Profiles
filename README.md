Search GitHub Profiles

This project is a simple web application that allows users to search for GitHub profiles by username.
When a user enters a GitHub username and submits the form, the app retrieves and displays the user's profile information,
including their avatar, name, bio, followers, following, and public repositories.

Also added nice error handling features
If a user is not found (e.g., if the username doesn't exist on GitHub), the app shows an error message stating that no profile was found.
It also handles errors that may occur when fetching repositories.

Technologies Used:
HTML/CSS: For the basic structure and styling of the web page.
JavaScript: For handling user input, making API requests, and dynamically updating the DOM.
Axios: A promise-based HTTP client used for making requests to the GitHub API.
