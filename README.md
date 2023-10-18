# Todo API using FastAPI (Without Database)

This is a simple RESTful API for managing a todo list using FastAPI. It does not use a database and instead stores the data in a list.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/vishalyadav28/todo_api.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo-api-fastapi
   ```

3. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required packages:
   ```bash
   pip3 install -r requirements.txt
   ```

## Usage

1. Start the FastAPI application:
   ```bash
   uvicorn main:app --reload
   ```

2. Open your web browser and go to `http://localhost:8000` to access the API documentation.

3. You can now use the API to manage your todo list.

## API Endpoints

- `GET /todos`: Get a list of all todos.
- `GET /todos/{todo_id}`: Get details of a specific todo.
- `POST /todos`: Create a new todo.
- `PUT /todos/{todo_id}`: Update an existing todo.
- `DELETE /todos/{todo_id}`: Delete a todo.


## Acknowledgments

- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/)



Happy coding!
