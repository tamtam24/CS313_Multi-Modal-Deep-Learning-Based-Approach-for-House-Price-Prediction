# Flask API Project

This project is a Flask RESTful API that connects to a MySQL database and utilizes a pre-trained machine learning model for predictions.

## Project Structure

```
flask-api-project
├── app
│   ├── __init__.py
│   ├── config.py
│   ├── models
│   │   └── model.py
│   ├── routes
│   │   └── api.py
│   └── utils
│       └── database.py
├── migrations
├── requirements.txt
├── run.py
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd flask-api-project
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

4. **Configure the database:**
   Update the `app/config.py` file with your MySQL database connection details.

5. **Run migrations:**
   ```
   flask db upgrade
   ```

6. **Run the application:**
   ```
   python run.py
   ```

## Usage

- The API provides endpoints for making predictions using the loaded model.
- You can access the API documentation (if available) or use tools like Postman to interact with the endpoints.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License.#   C S 3 1 3 _ M u l t i - M o d a l - D e e p - L e a r n i n g - B a s e d - A p p r o a c h - f o r - H o u s e - P r i c e - P r e d i c t i o n  
 