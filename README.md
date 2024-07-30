# Go Postgres

This is a simple Todo List application built using Go, Fiber, and PostgreSQL. The application demonstrates basic CRUD operations and integrates with DataDog for tracing.

## Features

- List and store simple text
- Use Fiber web framework
- PostgreSQL database integration
- Datadog tracing

## Installation

To install and run this project locally, follow these steps:

1. Copy the URL to the repo, but do not clone it: `https://github.com/your-username/go-postres.git`
2. Ensure Docker is installed and running on your machine
3. Enable [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) extension in VSCode 
4. From the Command Palatte (CTRL/Command+Shift+P), type and select `Dev Containers: Clone Repository in Container Volume...`
5. Choose Remote Source GitHub, and supply/choose the `go-postgres` repo
6. Once all containers are built and running, use `go run .` to start the app

## Usage

Once the server is running, navigate to (http://localhost:3000) and interact with the GUI.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).