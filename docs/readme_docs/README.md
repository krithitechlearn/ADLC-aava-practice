# Tic Tac Toe Game API Backend

---

## Description

A backend API service for playing the classic Tic Tac Toe game. This project provides endpoints to create and manage game sessions, make moves, check game status, and handle game logic for two players. Designed for easy integration with frontend clients or other services.

## Features

- Start a new Tic Tac Toe game session
- Make moves for each player (X and O)
- Validate moves and game state
- Check for win, draw, or ongoing status
- Retrieve current game board and status
- RESTful API design

## Installation

```bash
# Clone the repository
https://github.com/ADLC-aava-practice.git

# Navigate to the project directory
cd ADLC-aava-practice

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Folder Structure

- `docs/readme_docs/` - Project documentation (README.md)
- `text_files/` - Additional project details (details.txt)
- `app/` - Main application code (API endpoints, game logic)
- `tests/` - Unit and integration tests
- `requirements.txt` - Python dependencies

## Usage

1. Start the backend server (e.g., using Flask or FastAPI):
   ```bash
   python app/main.py
   ```
2. Interact with the API using tools like curl, Postman, or integrate with a frontend client.

## API Endpoints (Sample)

- `POST /games` - Start a new game
- `POST /games/{id}/move` - Make a move
- `GET /games/{id}` - Get game state

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.
