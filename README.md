# 🐍 Snake Game in Rust

A classic Snake game built in Rust using the [piston_window](https://docs.rs/piston_window/latest/piston_window/) graphics library. Guide your snake to eat food, grow longer, and avoid hitting the walls or yourself!

---

## 📜 Description

This is a simple implementation of the Snake game using Rust. The game window shows a grid where:
- The snake moves in the chosen direction
- Food appears at random locations
- The snake grows when it eats food
- Game over happens if the snake collides with the wall or itself

---

## ✨ Features

- Smooth grid-based movement using `piston_window`
- Random food generation avoiding snake's body
- Growing tail on eating
- Collision detection with walls and self
- Game over screen with auto-restart after delay

---

## 🛠️ Installation

1️⃣ Make sure you have Rust installed. If not, install it via [rustup](https://rustup.rs):

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh



2️⃣ Clone this repository:

git clone <YOUR_REPO_URL>
cd <YOUR_PROJECT_FOLDER>


3️⃣ Build the project:

cargo build



▶️ Usage
Run the game in debug mode:

cargo run



Or build and run the release version for better performance:
cargo run --release



Use your keyboard arrow keys to control the snake:

⬆️ Up
⬇️ Down
⬅️ Left
➡️ Right

Press ESC to close the window.


src/
  ├── main.rs       # Entry point: window setup and game loop
  ├── game.rs       # Game state: food, borders, input, updates
  ├── snake.rs      # Snake logic: movement, collision, growth
  └── draw.rs       # Rendering helpers: drawing blocks and rectangles
Cargo.toml          # Project metadata and dependencies


![screenshot](https://github.com/shwet91/snake-game-rust/blob/9bd9150648458eca186c6d502fa9597f7b330b86/Screenshot.png)

[https://github.com/shwet91/snake-game-rust/blob/9bd9150648458eca186c6d502fa9597f7b330b86/Screenshot.png](https://github.com/shwet91/snake-game-rust/blob/main/Screenshot.png?raw=true)


![screen](https://github.com/shwet91/snake-game-rust/blob/main/Screenshot.png?raw=true)


📜 Dependencies
piston_window for rendering

rand for random food placement

These are already in your Cargo.toml:



[dependencies]
piston_window = "0.127.0"  # (or your version)
rand = "0.8"               # (or your version)


MIT License

Copyright (c) 2025 YOUR_NAME

Permission is hereby granted, free of charge...


🙏 Acknowledgments
Piston developers for the graphics library

Rust community for tooling and support

🚀 Author
Shwet_praksh
