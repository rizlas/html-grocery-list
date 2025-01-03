# MiColtivo

MiColtivo is a web application designed to showcase a gallery of products with dynamic
filtering capabilities. It uses an external CSV file hosted on a GitHub Gist as the data
source and enables users to search and filter items by product name, code, and group.
The project was co-developed with ChatGPT, leveraging collaborative AI-assisted
development to enhance functionality and usability.

## Features

- **Dynamic Data Fetching**: Fetches and parses a CSV file hosted on a GitHub Gist.
- **Search Functionality**: Provides a search bar to filter products by name or code.
- **Group-Based Filtering**: Includes checkboxes to filter products by predefined
  groups: `freschi`, `trasformati`, and `esterni`.
- **Responsive Design**: Ensures compatibility across various devices using responsive
  techniques.
- **Error Handling**: Displays fallback data when errors occur during the fetch process.

## Technologies Used

- **HTML5**: Provides the structure of the web page.
- **CSS**: Styles the layout and components.
- **JavaScript**: Implements interactivity, data fetching, and dynamic rendering.
- **PapaParse**: A JavaScript library used for parsing CSV files.
- **GitHub Gist**: Hosts the external CSV file for data.
- **Placehold.co**: Generates placeholder images for products without specific images.

## How It Works

1. **Data Fetching**:
   - The application fetches a CSV file from a specified GitHub Gist using the GitHub
     API.
   - The CSV file is parsed into a JavaScript array of objects using PapaParse.

2. **Search and Filter**:
   - Users can search for products by typing into the search bar. The gallery updates in
     real time based on the query.
   - Users can filter products by group (`freschi`, `trasformati`, `esterni`) using
     checkboxes. The gallery displays only the selected groups.

3. **Dynamic Rendering**:
   - Products are displayed in a card-based layout.
   - Cards include a product image, name, code, price, and VAT information.

## External Data Source

The application uses the following Gist as its data source: [GitHub Gist CSV
File](https://api.github.com/gists/e9befc8c5f82912be9bbb7e51eb0e21d)

The Gist contains a CSV file with fields such as:

- `prodotto` (Product Name)
- `codice` (Product Code)
- `prezzo` (Price)
- `iva` (VAT)
- `immagine` (Image URL)
- `colore_sfondo` (Background Color)
- `gruppo` (Product Group)

## Setup and Usage

1. Clone or download the repository.
2. Ensure you have an internet connection to fetch the CSV data from the Gist.
3. Open the `index.html` file in a web browser to view the application.

## Development Notes

This project was co-developed with **ChatGPT**, an AI language model developed by
OpenAI. ChatGPT assisted with feature ideation, code structuring, and debugging,
ensuring an efficient and collaborative development process.

---

Feel free to make pull requests, fork, destroy or whatever you like most. Any criticism is more than welcome.

<br/>

<div align="center"><img src="https://avatars1.githubusercontent.com/u/8522635?s=96&v=4"/></div>
<p align="center">#followtheturtle</p>
