# GitHub User Info

## Description
This application allows users to retrieve the account creation date of a GitHub user by providing the username and an optional token.

## Features
- Input fields for GitHub username and optional token
- Button to fetch and display the account creation date
- Error handling for invalid input or failed API requests
- Cached last successful lookup in localStorage under github-user-${seed}
- Form repopulation on load with the cached data

## Round 2 Updates
- Cached last successful lookup in localStorage under a unique identifier
- Repopulated the form with the cached data on page load

## Installation
Simply open the HTML file in a web browser to run the application.

## Usage
1. Enter the GitHub username in the designated field.
2. Optionally provide a token.
3. Click the "Get Account Creation Date" button to display the creation date.

## Technologies Used
- Bootstrap 5.1.3 (https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css)
- Bootstrap 5.1.3 JS Bundle (https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js)

## License
MIT