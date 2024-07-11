# ByteNodes Hosting

Welcome to ByteNodes Hosting! This is a self-hosted, dynamic HTTP server for managing and serving files. With support for both light and dark modes, ByteNodes Hosting provides a modern UI for an efficient and user-friendly experience.

## Features

- **Dynamic File Display:** Serve files dynamically from a specified `files` folder.
- **Light/Dark Mode:** Toggle between light and dark mode with a convenient button.
- **Modern UI:** An updated interface for improved user experience.
- **Self-Hosted Image Hosting:** Host images locally with no limits.

## Getting Started

Follow these instructions to set up and run ByteNodes Hosting on your own server.

### Prerequisites

- Python 3.x
- Basic knowledge of HTML, CSS, and Python

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/bytesnodes-hosting.git
    cd bytesnodes-hosting
    ```

2. **Set up the environment:**

    Ensure you have Python 3.x installed. Optionally, set up a virtual environment:

    ```sh
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the server:**

    ```sh
    python server.py
    ```

5. **Access the server:**

    Open your web browser and go to `http://localhost:8000`.

### Configuration

- **Files Folder:** The server dynamically serves files from the `files` folder. Add or remove files in this folder to update the content served by the server.
- **Light/Dark Mode Toggle:** The toggle button is located at the bottom left corner of the UI, providing an easy switch between modes.

### Usage

- **Serving Files:** Place your files in the `files` folder. These will be accessible via the server's UI.
- **Image Hosting:** Upload images to the `files` folder for self-hosted, unlimited image hosting.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. **Fork the repository**
2. **Create a new branch (`git checkout -b feature-branch`)**
3. **Commit your changes (`git commit -am 'Add new feature'`)**
4. **Push to the branch (`git push origin feature-branch`)**
5. **Create a new Pull Request**

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries, please contact us at contact@bytesnodes.xyz.
