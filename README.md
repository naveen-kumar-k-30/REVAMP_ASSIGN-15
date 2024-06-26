# REVAMP_ASSIGN-15

# Bacon Ipsum API Fetcher

This project is a simple web application that fetches data from the Bacon Ipsum API and displays it on the webpage. The project demonstrates the use of HTML, Tailwind CSS for styling, and JavaScript for fetching API data and manipulating the DOM.

## Features

- Fetches random text data from the Bacon Ipsum API.
- Displays the fetched data on the webpage.
- Shows a loading spinner while fetching data.
- Handles errors gracefully and displays an error message if the API fetch fails.

## Technologies Used

- HTML
- Tailwind CSS
- JavaScript

### Prerequisites

You need a web browser to view the project. Ensure you have a modern web browser installed.

### Installation

```markdown

1. Clone the repository to your local machine:

    ```sh
    git clone https://github.com/naveen-kumar-k-30/bacon-ipsum-api-fetcher.git
    ```

2. Navigate to the project directory:

    ```sh
    cd bacon-ipsum-api-fetcher
    ```

3. Open the `index.html` file in your web browser.

### Usage

1. Open `index.html` in your web browser.
2. Click the `GET` button to fetch data from the Bacon Ipsum API.
3. The fetched data will be displayed in the message area.
4. While fetching data, a loading spinner will be displayed to indicate processing.
5. If an error occurs while fetching data, an error message will be displayed.

## Project Structure

```plaintext
.
├── index.html
├── README.md
```

- `index.html`: The main HTML file containing the structure and script for the web application.
- `README.md`: This file, providing an overview and instructions for the project.

## Code Explanation

### HTML

The HTML file contains the structure of the webpage. It includes:
- A message area to display the fetched data or error messages.
- A button to initiate the data fetch.
- A loading spinner to indicate that data is being fetched.

### CSS

Tailwind CSS is used for styling. The CDN for Tailwind CSS is included in the `<head>` section of the HTML file.

### JavaScript

The JavaScript code handles the logic for fetching data from the Bacon Ipsum API and updating the DOM:
- `fetchData`: An asynchronous function that fetches data from the API and updates the message area.
- Event listener on the `GET` button to call `fetchData` when clicked.
- Loading spinner visibility is toggled based on the fetching state.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the existing coding style and includes appropriate comments.

