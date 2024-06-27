# Books FastAPI

Books API is a simple RESTful API service built using FastAPI.

## Description

This project provides endpoints to manage a collection of books. It allows users to perform CRUD operations (Create, Read, Update, Delete) on books via HTTP requests.

## Features

- **CRUD Operations:** Allows creating, reading, updating, and deleting books.
- **Validation:** Validates input data to ensure correctness using PydanticV2.
- **FastAPI:** Built using FastAPI framework for Python, ensuring fast and efficient performance.
- **Swagger UI:** Includes Swagger UI for interactive documentation of API endpoints.

## Requirements

- Python 3.x
- FastAPI

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tahzeer/books-api.git
   ```

2. Install dependencies using `pip` (assuming `pip` is already installed):

   ```bash
   pip install fastapi uvicorn[standard]
   ```

   - `fastapi` is the FastAPI framework.
   - `uvicorn[standard]` is the ASGI server for running FastAPI applications. The `[standard]` option includes all recommended dependencies for production use.

   If you prefer to install them from `requirements.txt`, navigate to the project directory (`books-api`) and run:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the server:

   ```bash
   uvicorn app:app --reload
   ```

   - `main` is the name of the Python file (`app.py`).
   - `app` refers to the FastAPI instance created in `app.py`.
   - `--reload` enables auto-reloading on code changes (for development).

2. Open your browser and go to `http://localhost:8000/docs` to view the Swagger UI.
   
   - This interactive documentation provides details about the API endpoints, request/response formats, and allows testing API calls.

3. Use API endpoints as needed to manage the books collection.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- FastAPI Docs: https://fastapi.tiangolo.com/
- PydanticV2 Docs: https://docs.pydantic.dev/latest/
