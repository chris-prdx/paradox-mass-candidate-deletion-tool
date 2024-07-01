
# Paradox Mass Update Tool

This tool provides a simple web interface and server setup to handle requests for deleting candidates in the Paradox CEM. It's built with Node.js and Express, and features a basic HTML frontend.

## Getting Started

### Dependencies

- Node.js
- npm (Node Package Manager)

### Installing

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/chris-prdx/paradox-mass-candidate-deletion-tool
   ```

2. Navigate to the project directory:
   ```bash
   cd [Your Project Directory Name]
   ```

3. Make the install script executable:
   ```bash
   chmod +x setup-mass-update.sh
   ```
4. Run the install script:
   ```bash
   ./setup-mass-update.sh
   ```

Once the server is running, open `localhost:3000/main` in your web browser to interact with the tool.

## Usage

This tool allows you to submit requests to delete candidates. Fill in the required information in the web form and submit it. The server will handle these requests as per the configured logic.

## Contributing

Contributions to this project are welcome. To contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Author

- Chris Garcia

## License

This project is licensed under the MIT License - see the LICENSE file for details.
