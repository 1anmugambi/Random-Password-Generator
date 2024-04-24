# Random Password Generator

This is a simple web application that generates a random password. Users can click a button to generate a new random password, and they also have the option to copy the generated password to their clipboard.

## How to Use

1. Open the `index.html` file in your web browser.
2. Click the "Generate Password" button to generate a new random password.
3. Optionally, click the copy icon next to the generated password to copy it to your clipboard.

## Features

- Generates a random password with a length of 16 characters.
- Includes uppercase letters, lowercase letters, numbers, and special symbols in the generated password.
- Provides the ability to copy the generated password to the clipboard.

## Technologies Used

- HTML: Provides the structure of the web page.
- CSS: Styles the appearance of the web page.
- JavaScript: Generates the random password and handles copy functionality.

## Directory Structure

- `index.html`: Contains the HTML markup for the web page.
- `style.css`: Contains the CSS styles for the web page.
- `script.js`: Contains the JavaScript code for generating the random password and handling copy functionality.
- `images`: Directory containing images used in the web page.

## Acknowledgements

The random password generation logic is based on JavaScript's `Math.random()` function. The copy functionality uses the `document.execCommand("copy")` method.