# Chess AI

A simple yet powerful chess engine and interface built using Flask. This project combines "chessboard.js" and "chess.js" for the frontend chessboard logic with "python-chess" for backend chess logic. The calculations are performed server-side using Python, offering precise gameplay and AI support.

## Features

- Interactive chessboard using `chessboard.js` and `chess.js`.
- Backend-powered move validation and AI calculations with `python-chess`.
- Flask-based backend to handle game logic and state.
- Supports UCI engines and Gaviota endgame tablebases for advanced chess computations.

## Prerequisites

Before running this application, ensure the following are installed:

1. **Python** (3.6 or later)
2. **pip** (Python package installer)


## Installation

Follow these steps to set up and run the application:

### Step 1: Clone the Repository

git clone ''
cd ''


### Step 2: Install Required Packages

#### Install Flask:

pip install flask

#### Install Python Chess:

pip install python-chess[uci,gaviota]

## Running the Application

1. Navigate to the project directory.
2. Start the Flask server:
   python app.py
3. Open your web browser and go to:
   http://127.0.0.1:5000

## How It Works

- **Frontend**:  
  - Uses **chessboard.js** for rendering the chessboard.  
  - Implements **chess.js** for move validation and basic game mechanics.

- **Backend**:  
  - Flask provides the API to manage game states and user interactions.  
  - **python-chess** handles backend logic, including move generation, legality checks, and AI computations.

## Contributions

Contributions are welcome! Fork the repository, make your enhancements, and submit a pull request.

## License

This project is licensed under the MIT License. Use, modify, and share freely under the terms of this license.

Enjoy playing chess with **Chess AI**! 😊♟️