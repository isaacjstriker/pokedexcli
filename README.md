# pokedexcli

A command-line Pokédex application built in Go.

## About

This project was created as part of the Boot.dev backend developer course. It is a CLI tool that allows users to explore Pokémon locations, catch Pokémon, and manage their own Pokédex using data from the [PokeAPI](https://pokeapi.co/).

Just as a side note, it took me a decent amount of time to get this project finished. And I love what I've learned so far on Boot.dev!

## Features

- Explore Pokémon locations and see which Pokémon can be found there
- Attempt to catch Pokémon and add them to your personal Pokédex
- Inspect details about caught Pokémon
- Paginate through available locations
- Simple REPL interface for interactive use

## Technologies Used

- **Go**: Main programming language
- **PokeAPI**: Public Pokémon REST API for data
- **Standard Library**: For HTTP requests, JSON parsing, and CLI interaction
- **Custom Caching**: In-memory cache for API responses

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/isaacjstriker/pokedexcli.git
   cd pokedexcli
    ```

2. **Build the project:**
    ```sh
    go build
    ```

3. **Run the CLI:**
    ```sh
    ./pokedexcli
    ```

## Usage

Once running, use these commands to navigate the program:

- help — Show available commands
- map — List next page of locations
- mapb — List previous page of locations
- explore <location_name> — Show Pokémon in a location
- catch <pokemon_name> — Attempt to catch a Pokémon
- inspect <pokemon_name> — View details about a caught Pokémon
- pokedex — List all caught Pokémon
- exit — Exit the application

## License

This project is for educational purposes as part of the Boot.dev backend developer course.