# User Data Fetcher

This project demonstrates the use of the JavaScript Fetch API to retrieve user data from a public API and display it dynamically on a webpage. It covers fundamental concepts of asynchronous JavaScript, JSON parsing, error handling, and DOM manipulation.

## Table of Contents

-   [Objective](#objective)
-   [Live Demo](#live-demo)
-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [API Used](#api-used)
-   [Getting Started](#getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installation](#installation)
    -   [Running the Application](#running-the-application)
-   [Usage](#usage)
-   [Error Handling](#error-handling)
-   [Project Structure](#project-structure)
-   [Outcome](#outcome)
-   [Contributing](#contributing)
-   [License](#license)

## Objective

The primary objective of this task was to build a simple web application that fetches user data from a public API and displays it on the page, reinforcing key JavaScript concepts.


## Features

* *Dynamic Data Fetching:* Fetches user information from an external API when the page loads.
* *User-Friendly Display:* Presents user name, email, and address in a structured and styled format.
* *Reload Functionality:* A dedicated button to refetch and update user data.
* *Error Handling:* Displays a clear message to the user if data fetching fails (e.g., due to network issues or API errors).
* *Responsive Styling:* Basic CSS styling to improve readability and presentation.

## Technologies Used

* *HTML5:* For the basic structure of the webpage.
* *CSS3:* For styling the user cards and general page layout.
* *JavaScript (ES6+):*
    * *Fetch API:* For making asynchronous HTTP requests.
    * *Async/Await:* For handling asynchronous operations in a more synchronous-like manner.
    * *DOM Manipulation:* For dynamically creating and inserting elements into the HTML.

## API Used

The project fetches user data from the following public API:
https://jsonplaceholder.typicode.com/users

This API provides mock data for various resources, ideal for testing and development purposes.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

* A web browser (Google Chrome is recommended for development and debugging).
* A code editor (VS Code is recommended).
* (Optional, but recommended) VS Code Live Server extension for easy local development.
* Git installed on your machine.
* A GitHub account (for deploying the live demo).

### Running the Application

There are two primary ways to run this application locally, and one for live deployment:


## Usage

* Upon opening the index.html page (either locally or via the live demo), the application will automatically attempt to fetch and display user information.
* If data is loaded successfully, you will see a list of user cards.
* Click the "Reload Users" button to fetch and display the data again.

## Error Handling

The application includes basic error handling for network requests:

* If the Fetch API encounters a network error (e.g., no internet connection), or if the API returns a non-2xx HTTP status code, an error message will be displayed on the page instead of the user data.
* You can test this by disabling your internet connection and then clicking the "Reload Users" button.
