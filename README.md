# Pokédex
Access the Pokédex here: https://lucasyuki01.github.io/Pokedex/

An interactive web application that allows users to search for Pokémon by name or number and view their stats in a radar chart.

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Pokédex was developed using HTML, CSS, and JavaScript. The application consumes data from the [PokeAPI](https://pokeapi.co/) and displays it in a visually engaging way.

## Demo

You can access the live Pokédex [here](https://lucasyuki01.github.io/Pokedex/).

## Features

- Search for Pokémon by name or number.
- Navigate through Pokémon using Next and Previous buttons.
- Display an animated image of the Pokémon.
- Show the Pokémon's name, number, type, weight, and height.
- View Pokémon stats in a radar chart.

## Installation

To run the project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Lucasyuki01/Pokedex.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Pokedex
   ```

3. Open the `index.html` file in your browser:
   ```bash
   open index.html
   ```

## Usage

1. Enter a Pokémon's name or number in the search bar and press Enter.
2. Use the "Prev" and "Next" buttons to browse through Pokémon.
3. View the Pokémon's image, name, number, type, weight, height, and stats on the radar chart.

## Project Structure

```
pokedex/
├── css/
│   └── style.css
├── images/
│   ├── favicon-16x16.png
│   ├── pokedex-direita.png
│   └── pokedex-esquerda.png
├── js/
│   └── script.js
├── index.html
└── README.md
```

- `css/style.css`: Contains styling for the Pokédex.
- `images/`: Contains project images.
- `js/script.js`: Contains JavaScript code for interacting with the PokeAPI and manipulating the DOM.
- `index.html`: The HTML structure of the Pokédex.

## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

1. Fork the project.
2. Create a new branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Make your changes and commit:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a pull request.

## License

This project is open-source and available under the MIT License.
