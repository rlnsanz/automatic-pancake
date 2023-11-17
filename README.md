# My Flask App

This is a simple Flask/Jinja2 web application.

## Project Structure

The project has the following structure:

```
my-flask-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── templates
│   │   ├── base.html
│   │   └── index.html
│   └── static
│       ├── css
│       │   └── main.css
│       └── js
│           └── main.js
├── tests
│   └── __init__.py
├── config.py
├── run.py
└── README.md
```

## Setup

To set up the application, follow these steps:

1. Clone the repository.
2. Install the required packages using pip:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python run.py
```

The application will start on `localhost:5000`.

## Testing

To run the tests, use the following command:

```bash
python -m unittest discover tests
```

## Contributing

If you want to contribute to this project, please fork the repository, make your changes, and open a pull request.