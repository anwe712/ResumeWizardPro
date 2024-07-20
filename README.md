# Resume Builder with AI-Generated LaTeX Code

This project is a simple web application that allows users to create resumes by filling out a form. The form data is sent to a backend server, which uses OpenAI's API to generate LaTeX code for the resume based on the provided information.

## Features

- User-friendly form for inputting resume information
- Backend server to handle form submissions and interact with OpenAI API
- AI-generated LaTeX code for resumes

## Technologies Used

- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- Axios
- OpenAI API

## Prerequisites

- Node.js installed
- OpenAI API key

## Setup and Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/resume-builder.git
    cd resume-builder
    ```

2. Install the necessary dependencies:

    ```sh
    npm install
    ```

3. Create a `.env` file in the root directory and add your OpenAI API key:

    ```env
    AI_API_KEY=your_openai_api_key_here
    ```

4. Start the backend server:

    ```sh
    node server.js
    ```

    The server will run on `http://localhost:8088`.

5. Open the `index.html` file in your browser to view the form.

## Project Structure

```plaintext
.
├── index.html
├── script.js
├── styles.css
├── server.js
└── README.md
