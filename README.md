# Go Web Server Example

This is a simple Go web server project that demonstrates handling routes, processing form data, and serving static files.

## Features

- **Static File Serving:** Static files (e.g., HTML, CSS, JS) are served from the "./static" directory using `http.FileServer`.

- **Form Handling:** The "/form" route handles form submissions. It parses form data for POST requests and prints a success message along with the values of "name" and "address" form fields.

- **Hello Route:** The "/hello" route responds with a "hello!" message for both GET and POST requests.
## Getting Started

Follow these steps to build and run the project locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repo
    ```

3. Build the project:

    ```bash
    go build
    ```

4. Run the project:

    ```bash
    ./your-repo
    ```

5. Open your browser and visit [http://localhost:8080](http://localhost:8080) to interact with the web server.

