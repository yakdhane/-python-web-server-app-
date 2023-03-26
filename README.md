Sure, here is the beautifully formatted README.md file:

```markdown
# Python Web Server Application

This is a simple Python web server application that uses Flask to display "Hello, World!" on the homepage.

## Files

- `app.py`: This is the main Python file that contains the Flask application.
- `requirements.txt`: This file contains the list of Python packages required to run the application.
- `Dockerfile`: This file contains the instructions to build a Docker image for the application.

## Installation

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

## Usage

To run the application, execute the following command:

```bash
python app.py
```

This will start the Flask development server and the application will be accessible at `http://localhost:5000`.

## Docker

To build a Docker image for the application, run the following command:

```bash
docker build -t python-web-server .
```

This will build a Docker image with the tag `python-web-server`.

To run the Docker container, execute the following command:

```bash
docker run -p 80:80 python-web-server
```

This will start the Docker container and the application will be accessible at `http://localhost:80`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

I hope this helps!