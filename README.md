# Chat with SQL DB

## Overview
"Chat with SQL DB" is a project that allows users to interact with a SQL database through a chat interface. This project aims to simplify database operations by providing a conversational interface for executing SQL queries and retrieving data.

## Features
- **User Authentication**: Secure login and registration system.
- **Chat Interface**: Intuitive chat interface for interacting with the SQL database.
- **SQL Query Execution**: Execute SQL queries directly from the chat.
- **Data Retrieval**: Retrieve and display data from the database in a user-friendly format.
- **Error Handling**: Robust error handling for invalid queries and other issues.

## Technologies Used
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL/PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)

## Installation

### Prerequisites
- Python 3.x
- MySQL/PostgreSQL
- Node.js (for frontend dependencies)

### Steps
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/chat-with-sql-db.git
    cd chat-with-sql-db
    ```

2. **Set up the virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install backend dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up the database**:
    - Create a new database in MySQL/PostgreSQL.
    - Update the database configuration in `config.py`.

5. **Run database migrations**:
    ```sh
    flask db upgrade
    ```

6. **Install frontend dependencies**:
    ```sh
    cd frontend
    npm install
    ```

7. **Run the application**:
    ```sh
    flask run
    ```

## Usage
1. Open your web browser and navigate to `http://localhost:5000`.
2. Register a new account or log in with existing credentials.
3. Use the chat interface to interact with the SQL database.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please open an issue or contact the project maintainer at your-email@example.com.