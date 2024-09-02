##Tenor GIF Search Application

This project demonstrates a simple web application that allows users to search for GIFs using the Tenor API directly from a web interface. The application is built using HTML and JavaScript and leverages the Tenor API to fetch and display GIFs based on user queries.
Features

    Search for GIFs: Users can search for any GIF by entering keywords into the search bar. The application will fetch and display relevant GIFs from Tenor's vast collection.
    Responsive Design: The application is designed to be responsive, ensuring a smooth user experience across different devices and screen sizes.
    Easy Integration: The project uses a simple HTML file (tenor.html) and JavaScript to interact with the Tenor API, making it easy to understand and integrate into other projects.

Installation

To run this project locally, follow these steps:

    Clone the Repository:

    bash

git clone https://github.com/yourusername/tenor-gif-search.git
cd tenor-gif-search

Set Up Tenor API:

    Sign up for a Tenor API account here if you don't already have one.
    Obtain your API key from the Tenor developer portal.

Configure the Project:

    Open the tenor.html file in a text editor.
    Replace the placeholder for the API key with your actual Tenor API key.

javascript

    const API_KEY = 'YOUR_TENOR_API_KEY';

    Run the Application:
        Simply open the tenor.html file in any web browser to start searching for GIFs.

Usage

    Open the tenor.html file in a web browser.
    Use the search bar to enter any keyword related to the GIF you want to find.
    The application will display a list of GIFs that match your search query.
    Click on any GIF to view it in full size or to copy its link for sharing.

Project Structure

plaintext

tenor-gif-search/
├── tenor.html   # The main HTML file containing the search interface and logic.
└── README.md    # This README file.

API Reference

    Tenor API: The Tenor API is a simple and powerful way to search for GIFs. This project uses the /v1/search endpoint to fetch GIFs based on user queries.
        Base URL: https://g.tenor.com/v1/
        Search Endpoint: /v1/search?q={query}&key={API_KEY}&limit=10

Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgements

    Tenor API for providing an extensive collection of GIFs.

