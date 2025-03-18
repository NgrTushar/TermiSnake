# Rust CLI Snake Game

A simple command-line Snake game built in Rust. The game runs in the terminal and allows players to control a snake using arrow keys to collect food and grow in size. The game ends when the snake collides with itself.

## Features
- Classic Snake gameplay in the terminal
- Smooth movement with arrow keys
- Randomly placed food to grow the snake
- Game over condition when the snake collides with itself

## Installation
Ensure you have Rust installed on your system. If not, install Rust using [Rustup](https://rustup.rs/).

Clone this repository and navigate into the project directory:
```sh
git clone <repository-url>
cd <project-directory>
```

## Usage
To compile and run the game, execute the following command:
```sh
cargo run
```

## Controls
- **Arrow Keys**: Move the snake in the desired direction
- **Escape (Esc)**: Quit the game

## How It Works
- The game initializes a 15x30 grid.
- The snake moves in a specified direction and grows when it consumes food.
- If the snake collides with itself, the game ends.
- A separate thread handles the rendering and game logic while the main thread captures user input.

## Dependencies
This project uses the following Rust crates:
- `console` for handling terminal rendering and input
- `rand` for generating random food placements

## Future Improvements
- Add a scoring system
- Implement adjustable game speed
- Support for different terminal sizes
- Enhance UI with borders and colors

## License
This project is licensed under the MIT License.

