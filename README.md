# Example Open IA Api

This project is a simple Node.js application built with Express. It provides an API endpoint to handle questions and fetch responses from the OpenAI API.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/SoftwareSushi/example-open-ia-api
   ```

2. Navigate to the project directory:
   ```
   cd example-open-ia-api
   ```

3. Install the dependencies using pnpm:
   ```
   pnpm install
   ```

## Usage

To start the application, run the following command:
```
pnpm start
```

The application will be running on `http://localhost:3000`. You can send a POST request to the `/ask` endpoint with your question.


Example:
```
curl -X POST http://localhost:3000/ask \
     -H "Content-Type: application/json" \
     -d '{"question": "What is the capital of France?"}'
```
