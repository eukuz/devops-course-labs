# Crypto Prices Web App

A simple React web application that displays current Bitcoin and Ethereum prices using the CoinGecko API.

## Features

- Fetch and display the current prices of Bitcoin and Ethereum in USD.
- Modular design with separate components for displaying cryptocurrency prices and a refresh button.
- Uses best practices for fetching data and logging.

## Getting Started

### Prerequisites

- Node.js (v14.0 or higher recommended)
- npm (v6.0 or higher recommended)

### Installation

1. Clone the repository

2. Navigate to the project directory

3. Install the required packages:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

The application will now run on `http://127.0.0.1:3000`.

## Docker Usage

### How to Build?

To build the Docker image, navigate to the directory containing the `Dockerfile` and execute the following command:

```bash
docker build -t app_js .
```

### How to Pull?

You can pull the image using the following command:

```bash
pull eukuz/devops_course_js_app
```

### How to Run?

To run the Docker container from the image:

```bash
docker run -p 3000:3000 eukuz/devops_course_js_app 
```

After executing this command, you can access the application via `http://127.0.0.1:3000` in your browser.

## Usage

Open the application in a web browser. You'll see the current prices of Bitcoin and Ethereum displayed. Click the "Refresh" button or refresh the page to update the prices.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
